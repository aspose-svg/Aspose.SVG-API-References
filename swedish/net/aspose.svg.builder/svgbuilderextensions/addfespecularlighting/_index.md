---
title: "SVGBuilderExtensions.AddFeSpecularLighting"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddFeSpecularLighting metod. Lägger till en feSpecularLighting‑elementkonfiguration till byggaren. Detta element applicerar en ljuseffekt på bilden som simulerar spekulär reflektion."
type: docs
weight: 270
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addfespecularlighting/
---
## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting_2}

Lägger till en 'feSpecularLighting'-elementkonfiguration till byggaren. Detta element tillämpar en ljuseffekt på bilden och simulerar spekulär reflektion.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFESpecularLightingElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'feSpecularLighting'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEDistantLightElementBuilder&gt;, Color?, double?, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting}

Lägger till ett 'feSpecularLighting'-element i SVG-byggaren, vilket tillämpar en spekulär ljuseffekt med en angiven ljuskälla.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEDistantLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? specularConstant = null, double? specularExponent = null, 
    OneOf<double, (double, double)> kernelUnitLength = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFESpecularLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG‑byggarinstansen till vilken 'feSpecularLighting'-elementet kommer att läggas till. |
| lightSource | En åtgärd för att konfigurera ljuskällan för den spekulära ljuseffekten. |
| lightingColor | Färgen på ljuset. Valfri parameter. |
| surfaceScale | Skalfaktorn för ytan för ljuseffekten. Valfri parameter. |
| specularConstant | Konstanten som används för att skala den spekulära termen. Valfri parameter. |
| specularExponent | Exponenten för den spekulära termen, som styr fokuset för den spekulära högdagret. Valfri parameter. |
| kernelUnitLength | Kernel-enhetslängden för konvolutionsfiltret. Kan vara en double eller en ValueTuple av två doubles. Valfri parameter. |
| in | Indata-bilden som spekulära ljuseffekten kommer att tillämpas på. Kan vara en sträng eller en FilterInput. Valfri parameter. |
| result | Resultatidentifieraren för detta filterprimitiv. Valfri parameter. |
| x | X-koordinaten för filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| y | Y-koordinaten för filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| width | Bredden på filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| height | Höjden på filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| fill | Fyllningsfärgen, målning eller målningstjänst-ID för elementet. Valfri parameter. |
| stroke | Streckfärgen, målning eller målningstjänst-ID för elementet. Valfri parameter. |
| id | Den unika identifieraren för filterprimitivelementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera SVGFESpecularLightingElementBuilder. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* class [SVGFEDistantLightElementBuilder](../../svgfedistantlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEPointLightElementBuilder&gt;, Color?, double?, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting_1}

Lägger till ett 'feSpecularLighting'-element i SVG-byggaren, vilket tillämpar en spekulär ljuseffekt med en angiven ljuskälla.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEPointLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? specularConstant = null, double? specularExponent = null, 
    OneOf<double, (double, double)> kernelUnitLength = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFESpecularLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG‑byggarinstansen till vilken 'feSpecularLighting'-elementet kommer att läggas till. |
| lightSource | En åtgärd för att konfigurera ljuskällan för den spekulära ljuseffekten. |
| lightingColor | Färgen på ljuset. Valfri parameter. |
| surfaceScale | Skalfaktorn för ytan för ljuseffekten. Valfri parameter. |
| specularConstant | Konstanten som används för att skala den spekulära termen. Valfri parameter. |
| specularExponent | Exponenten för den spekulära termen, som styr fokuset för den spekulära högdagret. Valfri parameter. |
| kernelUnitLength | Kernel-enhetslängden för konvolutionsfiltret. Kan vara en double eller en ValueTuple av två doubles. Valfri parameter. |
| in | Indata-bilden som spekulära ljuseffekten kommer att tillämpas på. Kan vara en sträng eller en FilterInput. Valfri parameter. |
| result | Resultatidentifieraren för detta filterprimitiv. Valfri parameter. |
| x | X-koordinaten för filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| y | Y-koordinaten för filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| width | Bredden på filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| height | Höjden på filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| fill | Fyllningsfärgen, målning eller målningstjänst-ID för elementet. Valfri parameter. |
| stroke | Streckfärgen, målning eller målningstjänst-ID för elementet. Valfri parameter. |
| id | Den unika identifieraren för filterprimitivelementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera SVGFESpecularLightingElementBuilder. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* class [SVGFEPointLightElementBuilder](../../svgfepointlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFESpotLightElementBuilder&gt;, Color?, double?, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting_3}

Lägger till ett 'feSpecularLighting'-element i SVG-byggaren, vilket tillämpar en spekulär ljuseffekt med en angiven ljuskälla.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFESpotLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? specularConstant = null, double? specularExponent = null, 
    OneOf<double, (double, double)> kernelUnitLength = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFESpecularLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG‑byggarinstansen till vilken 'feSpecularLighting'-elementet kommer att läggas till. |
| lightSource | En åtgärd för att konfigurera ljuskällan för den spekulära ljuseffekten. |
| lightingColor | Färgen på ljuset. Valfri parameter. |
| surfaceScale | Skalfaktorn för ytan för ljuseffekten. Valfri parameter. |
| specularConstant | Konstanten som används för att skala den spekulära termen. Valfri parameter. |
| specularExponent | Exponenten för den spekulära termen, som styr fokuset för den spekulära högdagret. Valfri parameter. |
| kernelUnitLength | Kernel-enhetslängden för konvolutionsfiltret. Kan vara en double eller en ValueTuple av två doubles. Valfri parameter. |
| in | Indata-bilden som spekulära ljuseffekten kommer att tillämpas på. Kan vara en sträng eller en FilterInput. Valfri parameter. |
| result | Resultatidentifieraren för detta filterprimitiv. Valfri parameter. |
| x | X-koordinaten för filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| y | Y-koordinaten för filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| width | Bredden på filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| height | Höjden på filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| fill | Fyllningsfärgen, målning eller målningstjänst-ID för elementet. Valfri parameter. |
| stroke | Streckfärgen, målning eller målningstjänst-ID för elementet. Valfri parameter. |
| id | Den unika identifieraren för filterprimitivelementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera SVGFESpecularLightingElementBuilder. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* class [SVGFESpotLightElementBuilder](../../svgfespotlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
