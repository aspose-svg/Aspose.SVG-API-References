---
title: "SVGBuilderExtensions.AddPolyline"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddPolyline-methode. Voegt een polyline-elementconfiguratie toe aan de builder."
type: docs
weight: 430
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addpolyline/
---
## AddPolyline<TBuilder>(*this TBuilder, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline_1}

Voegt een 'polyline'-elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, 
    Action<SVGPolylineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'polyline'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolyline<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline}

Voegt een 'polyline'-element toe aan de SVG-builder, waarbij de hoekpunten en stijlen worden gespecificeerd.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolylineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder, dat vloeiend API-gebruik mogelijk maakt. |
| builder | De SVG-builderinstantie waaraan het 'polyline'-element zal worden toegevoegd. |
| points | Een array van doubles die de punten van de polyline vertegenwoordigen (afwisselend x- en y-coördinaten). |
| fill | De vulkleur of schilderstijl voor de polyline. Kan een Color- of Paint-enumwaarde of een paint‑server-ID zijn. Optionele parameter. |
| stroke | De lijnkleur of schilderstijl voor de polyline. Kan een Color- of Paint-enumwaarde of een paint‑server-ID zijn. Optionele parameter. |
| id | De unieke identifier voor het polyline-element. Optionele parameter. |
| extend | Een optionele actie om de polyline-elementbuilder verder te configureren. |

### Retourwaarde

De builder‑instantie, waarmee method chaining mogelijk is.

### Zie ook

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
