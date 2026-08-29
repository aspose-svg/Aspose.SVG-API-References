---
title: "SVGBuilderExtensions.AddEllipse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddEllipse-methode. Voegt een ellips-elementconfiguratie toe aan de builder."
type: docs
weight: 120
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addellipse/
---
## AddEllipse<TBuilder>(*this TBuilder, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse_1}

Voegt een 'ellipse'‑elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    Action<SVGEllipseElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'ellipse'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddEllipse<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse}

Voegt een 'ellipse'‑element toe aan de SVG‑builder, met specificatie van het middelpunt, de stralen en de stijlen.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> rx = null, OneOf<double, (double, LengthType)> ry = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGEllipseElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder, dat vloeiend API-gebruik mogelijk maakt. |
| builder | De SVG-builderinstantie waaraan het 'ellipse'-element zal worden toegevoegd. |
| cx | De x-coördinaat van het midden van de ellips. Kan een double‑waarde of een tuple van double en LengthType zijn. |
| cy | De y-coördinaat van het midden van de ellips. Kan een double‑waarde of een tuple van double en LengthType zijn. |
| rx | De x-radius van de ellips. Kan een double‑waarde of een tuple van double en LengthType zijn. |
| ry | De y-radius van de ellips. Kan een double‑waarde of een tuple van double en LengthType zijn. |
| fill | De vulkleur of schilderstijl voor de ellips. Kan een Color of een Paint‑enumwaarde of een paint‑server‑ID zijn. Optionele parameter. |
| stroke | De lijnkleur of schilderstijl voor de ellips. Kan een Color of een Paint‑enumwaarde of een paint‑server‑ID zijn. Optionele parameter. |
| id | De unieke identifier voor het ellips‑element. Optionele parameter. |
| extend | Een optionele actie om de ellips‑elementbuilder verder te configureren. |

### Retourwaarde

De builder‑instantie, waarmee method chaining mogelijk is.

### Zie ook

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
