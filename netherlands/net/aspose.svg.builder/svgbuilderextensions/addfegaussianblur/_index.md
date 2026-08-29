---
title: "SVGBuilderExtensions.AddFeGaussianBlur"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddFeGaussianBlur methode. Voegt een feGaussianBlur-elementconfiguratie toe aan de builder. Dit element past een Gaussian blur toe op de invoerafbeelding"
type: docs
weight: 220
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addfegaussianblur/
---
## AddFeGaussianBlur<TBuilder>(*this TBuilder, Action&lt;SVGFEGaussianBlurElementBuilder&gt;*) {#addfegaussianblur_1}

Voegt een configuratie van het 'feGaussianBlur'-element toe aan de builder. Dit element past een Gaussiaanse vervaging toe op de invoerafbeelding.

```csharp
public static TBuilder AddFeGaussianBlur<TBuilder>(this TBuilder builder, 
    Action<SVGFEGaussianBlurElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie-actie voor het 'feGaussianBlur'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGFEGaussianBlurElementBuilder](../../svgfegaussianblurelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeGaussianBlur<TBuilder>(*this TBuilder, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEGaussianBlurElementBuilder&gt;*) {#addfegaussianblur}

Voegt een 'feGaussianBlur'-element toe aan de SVG builder, waarbij een Gaussiaanse vervagingseffect op de invoerafbeelding wordt toegepast.

```csharp
public static TBuilder AddFeGaussianBlur<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, double)> stdDeviation = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEGaussianBlurElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder, dat vloeiend API-gebruik mogelijk maakt. |
| builder | De SVG-builderinstantie waaraan het 'feGaussianBlur'-element zal worden toegevoegd. |
| stdDeviation | De standaarddeviatie voor de bluroperatie. Kan een double of een ValueTuple van twee doubles zijn. Optionele parameter. |
| in | De invoerafbeelding waarop de Gaussian blur wordt toegepast. Kan een string of een FilterInput zijn. Optionele parameter. |
| result | De resultaat‑identifier voor dit filter‑primitive. Optionele parameter. |
| x | De x-coördinaat van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| y | De y-coördinaat van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| width | De breedte van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| height | De hoogte van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| fill | De vulkleur, verf of paint server-id voor het element. Optionele parameter. |
| stroke | De lijnkleur, verf of paint server-id voor het element. Optionele parameter. |
| id | De unieke identifier voor het filterprimitive element. Optionele parameter. |
| extend | Een optionele actie om de SVGFEGaussianBlurElementBuilder verder te configureren. |

### Retourwaarde

De builder‑instantie, waarmee method chaining mogelijk is.

### Zie ook

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEGaussianBlurElementBuilder](../../svgfegaussianblurelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
