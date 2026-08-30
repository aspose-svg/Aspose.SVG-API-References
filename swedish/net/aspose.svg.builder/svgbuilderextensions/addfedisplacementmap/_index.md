---
title: "SVGBuilderExtensions.AddFeDisplacementMap"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddFeDisplacementMap-metoden. Lägger till en feDisplacementMap-elementkonfiguration i byggaren. Detta element förskjuter en bild med en specificerad vektorkarta"
type: docs
weight: 190
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addfedisplacementmap/
---
## AddFeDisplacementMap<TBuilder>(*this TBuilder, Action&lt;SVGFEDisplacementMapElementBuilder&gt;*) {#addfedisplacementmap}

Lägger till en 'feDisplacementMap'-elementkonfiguration till byggaren. Detta element förskjuter en bild med en angiven vektorkarta.

```csharp
public static TBuilder AddFeDisplacementMap<TBuilder>(this TBuilder builder, 
    Action<SVGFEDisplacementMapElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'feDisplacementMap'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGFEDisplacementMapElementBuilder](../../svgfedisplacementmapelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDisplacementMap<TBuilder>(*this TBuilder, double?, ChannelSelector?, ChannelSelector?, OneOf&lt;string, FilterInput&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDisplacementMapElementBuilder&gt;*) {#addfedisplacementmap_1}

Lägger till ett 'feDisplacementMap'-element till SVG-byggaren, som skapar en effekt som förvränger en bild baserat på färgdata från en andra källa.

```csharp
public static TBuilder AddFeDisplacementMap<TBuilder>(this TBuilder builder, double? scale = null, 
    ChannelSelector? xChannelSelector = default, ChannelSelector? yChannelSelector = default, 
    OneOf<string, FilterInput> @in = null, OneOf<string, FilterInput> in2 = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDisplacementMapElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG-byggarinstansen som 'feDisplacementMap'-elementet kommer att läggas till. |
| scale | Skalfaktorn som bestämmer mängden förskjutning. Valfri parameter. |
| xChannelSelector | Kanalen i in2-bilden som ska användas för förskjutning längs x-axeln. Valfri parameter. |
| yChannelSelector | Kanalen i in2-bilden som ska användas för förskjutning längs y-axeln. Valfri parameter. |
| in | Indata-bilden som ska förskjutas. Kan vara en sträng eller en FilterInput. Valfri parameter. |
| in2 | Bilden som tillhandahåller förskjutningsdata. Kan vara en sträng eller en FilterInput. Valfri parameter. |
| result | Resultatidentifieraren för detta filterprimitiv. Valfri parameter. |
| x | X-koordinaten för filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| y | Y-koordinaten för filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| width | Bredden på filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| height | Höjden på filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| fill | Fyllningsfärgen, målning eller målningstjänst-ID för elementet. Valfri parameter. |
| stroke | Streckfärgen, målning eller målningstjänst-ID för elementet. Valfri parameter. |
| id | Den unika identifieraren för filterprimitivelementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera SVGFEDisplacementMapElementBuilder. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* enum [ChannelSelector](../../channelselector/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDisplacementMapElementBuilder](../../svgfedisplacementmapelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
