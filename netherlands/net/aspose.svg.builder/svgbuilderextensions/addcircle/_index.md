---
title: "SVGBuilderExtensions.AddCircle"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddCircle method. Voegt een cirkel‑elementconfiguratie toe aan de builder."
type: docs
weight: 70
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addcircle/
---
## AddCircle<TBuilder>(*this TBuilder, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle_1}

Voegt een 'circle'‑elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    Action<SVGCircleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'circle'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddCircle<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle}

Voegt een 'circle'‑element met opgegeven middelpunt, radius en stijlen toe aan de SVG‑builder.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGCircleElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder, dat vloeiend API-gebruik mogelijk maakt. |
| builder | De SVG‑builder‑instantie waaraan het 'circle'-element zal worden toegevoegd. |
| cx | De x‑coördinaat van het middelpunt van de cirkel. Kan een double‑waarde of een tuple van double en LengthType zijn. |
| cy | De y‑coördinaat van het middelpunt van de cirkel. Kan een double‑waarde of een tuple van double en LengthType zijn. |
| r | De straal van de cirkel. Kan een double‑waarde of een tuple van double en LengthType zijn. |
| fill | De vulkleur of schilderstijl voor de cirkel. Kan een Color of een Paint‑enumwaarde of een paint‑server‑ID zijn. Optionele parameter. |
| stroke | De lijnkleur of schilderstijl voor de omtrek van de cirkel. Kan een Color of een Paint‑enumwaarde of een paint‑server‑ID zijn. Optionele parameter. |
| id | De unieke identifier voor het cirkel‑element. Optionele parameter. |
| extend | Een optionele actie om de cirkel‑element‑builder verder te configureren. |

### Retourwaarde

De builder‑instantie, waarmee method chaining mogelijk is.

### Zie ook

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
