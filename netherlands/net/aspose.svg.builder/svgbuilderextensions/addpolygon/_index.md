---
title: "SVGBuilderExtensions.AddPolygon"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddPolygon-methode. Voegt een configuratie van een polygon-element toe aan de builder"
type: docs
weight: 420
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addpolygon/
---
## AddPolygon<TBuilder>(*this TBuilder, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon_1}

Voegt een 'polygon'-elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, 
    Action<SVGPolygonElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'polygon'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolygon<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon}

Voegt een 'polygon'-element toe aan de SVG-builder, waarbij de hoekpunten en stijlen worden gespecificeerd.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolygonElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder, dat vloeiend API-gebruik mogelijk maakt. |
| builder | De SVG‑builder‑instantie waaraan het 'polygon'-element zal worden toegevoegd. |
| points | Een array van doubles die de punten van de polygon vertegenwoordigt (afwisselend x- en y-coördinaten). |
| fill | De vulkleur of schilderstijl voor de polygon. Kan een Color of een Paint‑enumwaarde of een paint‑server‑ID zijn. Optionele parameter. |
| stroke | De lijnkleur of schilderstijl voor de polygon. Kan een Color of een Paint‑enumwaarde of een paint‑server‑ID zijn. Optionele parameter. |
| id | De unieke identifier voor het polygon-element. Optionele parameter. |
| extend | Een optionele actie om de polygon-element‑builder verder te configureren. |

### Retourwaarde

De builder‑instantie, waarmee method chaining mogelijk is.

### Zie ook

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
