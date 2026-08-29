---
title: "SVGBuilderExtensions.AddFeTurbulence"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddFeTurbulence method. Voegt een feTurbulence‑elementconfiguratie toe aan de builder. Dit element maakt een afbeelding met behulp van Perlin‑ruis, nuttig voor het creëren van texturen zoals wolken of marmer."
type: docs
weight: 290
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addfeturbulence/
---
## AddFeTurbulence<TBuilder>(*this TBuilder, Action&lt;SVGFETurbulenceElementBuilder&gt;*) {#addfeturbulence_1}

Voegt een configuratie van het 'feTurbulence'-element toe aan de builder. Dit element maakt een afbeelding met Perlin‑ruis, nuttig voor het creëren van texturen zoals wolken of marmer.

```csharp
public static TBuilder AddFeTurbulence<TBuilder>(this TBuilder builder, 
    Action<SVGFETurbulenceElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'feTurbulence'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGFETurbulenceElementBuilder](../../svgfeturbulenceelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeTurbulence<TBuilder>(*this TBuilder, OneOf&lt;double, (double, double)&gt;, int?, double?, StitchTiles?, TurbulenceType?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFETurbulenceElementBuilder&gt;*) {#addfeturbulence}

Voegt een 'feTurbulence'-element toe aan de SVG-builder, waardoor een turbulentie-effect ontstaat, zoals wolken of marmer, met behulp van Perlin-ruis.

```csharp
public static TBuilder AddFeTurbulence<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, double)> baseFrequency = null, int? numOctaves = null, 
    double? seed = null, StitchTiles? stitchTiles = default, TurbulenceType? type = default, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFETurbulenceElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder, dat vloeiend API-gebruik mogelijk maakt. |
| builder | De SVG‑builder‑instantie waaraan het 'feTurbulence'-element zal worden toegevoegd. |
| baseFrequency | De basisfrequentie van de turbulentie. Kan een double of een ValueTuple van twee doubles zijn. Optionele parameter. |
| numOctaves | Het aantal octaven voor de turbulentie. Optionele parameter. |
| seed | Het seed‑nummer voor de willekeurige getalgenerator. Optionele parameter. |
| stitchTiles | Geeft aan of de tegels aan elkaar zijn gestikt. Optionele parameter. |
| type | Het type turbulentie (fractal noise of turbulence). Optionele parameter. |
| in | De invoerafbeelding waarop het turbulentie‑effect wordt toegepast. Kan een string of een FilterInput zijn. Optionele parameter. |
| result | De resultaat‑identifier voor dit filter‑primitive. Optionele parameter. |
| x | De x-coördinaat van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| y | De y-coördinaat van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| width | De breedte van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| height | De hoogte van de filterprimitive subregio. Kan een double of een ValueTuple met LengthType zijn. Optionele parameter. |
| fill | De vulkleur, verf of paint server-id voor het element. Optionele parameter. |
| stroke | De lijnkleur, verf of paint server-id voor het element. Optionele parameter. |
| id | De unieke identifier voor het filterprimitive element. Optionele parameter. |
| extend | Een optionele actie om de SVGFETurbulenceElementBuilder verder te configureren. |

### Retourwaarde

De builder‑instantie, waarmee method chaining mogelijk is.

### Zie ook

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [StitchTiles](../../stitchtiles/)
* enum [TurbulenceType](../../turbulencetype/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFETurbulenceElementBuilder](../../svgfeturbulenceelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
