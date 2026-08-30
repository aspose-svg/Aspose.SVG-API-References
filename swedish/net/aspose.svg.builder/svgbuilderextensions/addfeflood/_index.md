---
title: "SVGBuilderExtensions.AddFeFlood"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddFeFlood-metoden. Lägger till en feFlood-elementkonfiguration i byggaren. Detta element fyller filterdelområdet med en angiven färg."
type: docs
weight: 210
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addfeflood/
---
## AddFeFlood<TBuilder>(*this TBuilder, Action&lt;SVGFEFloodElementBuilder&gt;*) {#addfeflood}

Lägger till en 'feFlood'-elementkonfiguration till byggaren. Detta element fyller filterdelområdet med en angiven färg.

```csharp
public static TBuilder AddFeFlood<TBuilder>(this TBuilder builder, 
    Action<SVGFEFloodElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'feFlood'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGFEFloodElementBuilder](../../svgfefloodelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeFlood<TBuilder>(*this TBuilder, Color?, double?, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEFloodElementBuilder&gt;*) {#addfeflood_1}

Lägger till ett 'feFlood'-element i SVG-byggaren, vilket skapar en enhetlig färgöversvämningseffekt över hela filterdelområdet.

```csharp
public static TBuilder AddFeFlood<TBuilder>(this TBuilder builder, Color? floodColor = default, 
    double? floodOpacity = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEFloodElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG-byggarinstansen till vilken 'feFlood'-elementet kommer att läggas till. |
| floodColor | Färgen som används för översvämningseffekten. Valfri parameter. |
| floodOpacity | Opacitetsnivån för översvämningsfärgen. Valfri parameter. |
| result | Resultatidentifieraren för detta filterprimitiv. Valfri parameter. |
| x | X-koordinaten för filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| y | Y-koordinaten för filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| width | Bredden på filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| height | Höjden på filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| fill | Fyllningsfärgen, målning eller målningstjänst-ID för elementet. Valfri parameter. |
| stroke | Streckfärgen, målning eller målningstjänst-ID för elementet. Valfri parameter. |
| id | Den unika identifieraren för filterprimitivelementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera SVGFEFloodElementBuilder. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEFloodElementBuilder](../../svgfefloodelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
