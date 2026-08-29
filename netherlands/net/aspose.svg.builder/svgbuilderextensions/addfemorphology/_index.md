---
title: "SVGBuilderExtensions.AddFeMorphology"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddFeMorphology-methode. Voegt een feMorphology‑elementconfiguratie toe aan de builder. Dit element wordt gebruikt om morfologische bewerkingen zoals dilatatie of erosie op de invoerafbeelding toe te passen."
type: docs
weight: 250
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addfemorphology/
---
## AddFeMorphology<TBuilder>(*this TBuilder, Action&lt;SVGFEMorphologyElementBuilder&gt;*) {#addfemorphology}

Voegt een configuratie van het 'feMorphology'-element toe aan de builder. Dit element wordt gebruikt om morfologische bewerkingen zoals dilatatie of erosie op de invoerafbeelding toe te passen.

```csharp
public static TBuilder AddFeMorphology<TBuilder>(this TBuilder builder, 
    Action<SVGFEMorphologyElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'feMorphology'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGFEMorphologyElementBuilder](../../svgfemorphologyelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeMorphology<TBuilder>(*this TBuilder, MorphologyOperator?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEMorphologyElementBuilder&gt;*) {#addfemorphology_1}

Voegt een 'feMorphology'-element toe aan de SVG builder, waarbij een morfologische bewerking op de invoerafbeelding wordt toegepast.

```csharp
public static TBuilder AddFeMorphology<TBuilder>(this TBuilder builder, 
    MorphologyOperator? @operator = default, OneOf<double, (double, double)> radius = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEMorphologyElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder, dat vloeiend API-gebruik mogelijk maakt. |
| builder | De SVG-builderinstantie waaraan het 'feMorphology'-element zal worden toegevoegd. |
| operator | De morfologische operator die moet worden toegepast. Optionele parameter. |
| radius | De radius voor de morfologische bewerking. Kan een double of een ValueTuple van twee doubles zijn. Optionele parameter. |
| in | De invoerafbeelding waaraan de morfologische bewerking zal worden toegepast. Kan een string of een FilterInput zijn. Optionele parameter. |
| result | De resultaat‑identifier voor dit filter‑primitive. Optionele parameter. |
| x | De x-coördinaat van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| y | De y-coördinaat van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| width | De breedte van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| height | De hoogte van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| fill | De vulkleur, verf of paint server-id voor het element. Optionele parameter. |
| stroke | De lijnkleur, verf of paint server-id voor het element. Optionele parameter. |
| id | De unieke identifier voor het filterprimitive element. Optionele parameter. |
| extend | Een optionele actie om de SVGFEMorphologyElementBuilder verder te configureren. |

### Retourwaarde

De builder‑instantie, waarmee method chaining mogelijk is.

### Zie ook

* enum [MorphologyOperator](../../morphologyoperator/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEMorphologyElementBuilder](../../svgfemorphologyelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
