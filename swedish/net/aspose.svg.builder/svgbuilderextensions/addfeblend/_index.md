---
title: "SVGBuilderExtensions.AddFeBlend"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGBuilderExtensions AddFeBlend‑metoden. Lägger till en feBlend‑elementkonfiguration i byggaren. Detta element definierar en blandningseffekt mellan två grafikobjekt."
type: docs
weight: 130
url: /sv/net/aspose.svg.builder/svgbuilderextensions/addfeblend/
---
## AddFeBlend<TBuilder>(*this TBuilder, Action&lt;SVGFEBlendElementBuilder&gt;*) {#addfeblend}

Lägger till en 'feBlend'-elementkonfiguration till byggaren. Detta element definierar en blandningseffekt mellan två grafik.

```csharp
public static TBuilder AddFeBlend<TBuilder>(this TBuilder builder, 
    Action<SVGFEBlendElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-elementbyggaren. |
| byggare | Byggarinstansen. |
| konfigurera | Konfigurationsåtgärden för 'feBlend'-elementet. |

### Returvärde

Byggarinstansen för kedjning.

### Se även

* class [SVGFEBlendElementBuilder](../../svgfeblendelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeBlend<TBuilder>(*this TBuilder, BlendMode?, OneOf&lt;string, FilterInput&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEBlendElementBuilder&gt;*) {#addfeblend_1}

Lägger till ett 'feBlend'-element till SVG-byggaren, med angiven blandningsläge och olika andra egenskaper för filtereffekten.

```csharp
public static TBuilder AddFeBlend<TBuilder>(this TBuilder builder, BlendMode? mode = default, 
    OneOf<string, FilterInput> @in = null, OneOf<string, FilterInput> in2 = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEBlendElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beskrivning |
| --- | --- |
| TBuilder | Typen av SVG-byggarinstansen, som underlättar flytande API-användning. |
| byggare | SVG‑byggarinstansen som 'feBlend'-elementet kommer att läggas till. |
| mode | Blandningsläget som ska användas. Valfri parameter. |
| in | Den första inmatningen för blandningseffekten. Kan vara en sträng eller ett FilterInput. Valfri parameter. |
| in2 | Den andra inmatningen för blandningseffekten. Kan vara en sträng eller ett FilterInput. Valfri parameter. |
| result | Resultatidentifieraren för detta filterprimitiv. Valfri parameter. |
| x | X-koordinaten för filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| y | Y-koordinaten för filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| width | Bredden på filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| height | Höjden på filterprimitivets delområde. Kan vara en double eller en ValueTuple med LengthType. Valfri parameter. |
| fill | Fyllningsfärgen, målning eller målningstjänst-ID för elementet. Valfri parameter. |
| stroke | Streckfärgen, målning eller målningstjänst-ID för elementet. Valfri parameter. |
| id | Den unika identifieraren för filterprimitivelementet. Valfri parameter. |
| extend | En valfri åtgärd för att ytterligare konfigurera SVGFEBlendElementBuilder. |

### Returvärde

Builderinstansen, som möjliggör metodkedjning.

### Se även

* enum [BlendMode](../../blendmode/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEBlendElementBuilder](../../svgfeblendelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
