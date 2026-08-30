---
title: "SVGBuilderExtensions.AddFeColorMatrix"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddFeColorMatrix-metoden. Lägger till en feColorMatrix-elementkonfiguration till byggaren. Detta element tillämpar en matrisomvandling på färg- och alfavärdena för varje pixel"
type: docs
weight: 140
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addfecolormatrix/
---
## AddFeColorMatrix<TBuilder>(*this TBuilder, Action&lt;SVGFEColorMatrixElementBuilder&gt;*) {#addfecolormatrix_1}

Lägger till en 'feColorMatrix'-elementkonfiguration till byggaren. Detta element applicerar en matrisomvandling på färg- och alfavärdena för varje pixel.

```csharp
public static TBuilder AddFeColorMatrix<TBuilder>(this TBuilder builder, 
    Action<SVGFEColorMatrixElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för elementet 'feColorMatrix'. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGFEColorMatrixElementBuilder](../../svgfecolormatrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeColorMatrix<TBuilder>(*this TBuilder, [ColorMatrixOperation](../../colormatrixoperation/), double[], OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEColorMatrixElementBuilder&gt;*) {#addfecolormatrix}

Lägger till ett 'feColorMatrix'-element till SVG-byggaren, med angiven typ av färgmatrisoperation och olika andra egenskaper för filtereffekten.

```csharp
public static TBuilder AddFeColorMatrix<TBuilder>(this TBuilder builder, ColorMatrixOperation type, 
    double[] values = null, OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEColorMatrixElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG-byggarinstansen till vilken elementet 'feColorMatrix' kommer att läggas till. |
| type | Typen av färgmatrisoperation som ska tillämpas. |
| values | Värdena för färgmatrisoperationen. Valfri parameter. |
| in | Indatan för färgmatriseffekten. Kan vara en sträng eller ett FilterInput. Valfri parameter. |
| result | Resultatidentifieraren för detta filterprimitiv. Valfri parameter. |
| x | X-koordinaten för filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| y | Y-koordinaten för filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| width | Bredden på filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| height | Höjden på filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| fill | Fyllningsfärgen, målning eller målningstjänst-ID för elementet. Valfri parameter. |
| stroke | Streckfärgen, målning eller målningstjänst-ID för elementet. Valfri parameter. |
| id | Den unika identifieraren för filterprimitivelementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera SVGFEColorMatrixElementBuilder. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEColorMatrixElementBuilder](../../svgfecolormatrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
