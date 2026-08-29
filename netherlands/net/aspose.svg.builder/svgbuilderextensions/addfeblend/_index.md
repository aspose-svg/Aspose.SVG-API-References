---
title: "SVGBuilderExtensions.AddFeBlend"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddFeBlend-methode. Voegt een feBlend‑elementconfiguratie toe aan de builder. Dit element definieert een meng‑effect tussen twee afbeeldingen"
type: docs
weight: 130
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addfeblend/
---
## AddFeBlend<TBuilder>(*this TBuilder, Action&lt;SVGFEBlendElementBuilder&gt;*) {#addfeblend}

Voegt een 'feBlend'‑elementconfiguratie toe aan de builder. Dit element definieert een mengeffect tussen twee grafische elementen.

```csharp
public static TBuilder AddFeBlend<TBuilder>(this TBuilder builder, 
    Action<SVGFEBlendElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'feBlend'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGFEBlendElementBuilder](../../svgfeblendelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeBlend<TBuilder>(*this TBuilder, BlendMode?, OneOf&lt;string, FilterInput&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEBlendElementBuilder&gt;*) {#addfeblend_1}

Voegt een 'feBlend'‑element toe aan de SVG‑builder, met specificatie van de mengmodus en diverse andere eigenschappen voor het filtereffect.

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

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder, dat vloeiend API-gebruik mogelijk maakt. |
| builder | De SVG‑builder‑instantie waaraan het 'feBlend'-element zal worden toegevoegd. |
| mode | De te gebruiken mengmodus. Optionele parameter. |
| in | De eerste invoer voor het meng‑effect. Kan een string of een FilterInput zijn. Optionele parameter. |
| in2 | De tweede invoer voor het meng‑effect. Kan een string of een FilterInput zijn. Optionele parameter. |
| result | De resultaat‑identifier voor dit filter‑primitive. Optionele parameter. |
| x | De x-coördinaat van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| y | De y-coördinaat van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| width | De breedte van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| height | De hoogte van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| fill | De vulkleur, verf of paint server-id voor het element. Optionele parameter. |
| stroke | De lijnkleur, verf of paint server-id voor het element. Optionele parameter. |
| id | De unieke identifier voor het filterprimitive element. Optionele parameter. |
| extend | Een optionele actie om de SVGFEBlendElementBuilder verder te configureren. |

### Retourwaarde

De builder‑instantie, waarmee method chaining mogelijk is.

### Zie ook

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
