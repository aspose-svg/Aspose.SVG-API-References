---
title: "SVGBuilderExtensions.AddRect"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddRect-methode. Voegt een rect‑elementconfiguratie toe aan de builder."
type: docs
weight: 450
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addrect/
---
## AddRect<TBuilder>(*this TBuilder, Action&lt;SVGRectElementBuilder&gt;*) {#addrect_1}

Voegt een 'rect' elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    Action<SVGRectElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'rect'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRect<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGRectElementBuilder&gt;*) {#addrect}

Voegt een 'rect' (rechthoek) element met opgegeven afmetingen en stijlen toe aan de SVG builder.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGRectElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder, dat vloeiend API-gebruik mogelijk maakt. |
| builder | De SVG‑builder‑instantie waaraan het 'rect'-element zal worden toegevoegd. |
| x | De x‑coördinaat van het startpunt van de rechthoek. Kan een double‑waarde of een tuple van double en LengthType zijn. |
| y | De y‑coördinaat van het startpunt van de rechthoek. Kan een double‑waarde of een tuple van double en LengthType zijn. |
| width | De breedte van de rechthoek. Kan een double‑waarde of een tuple van double en LengthType zijn. |
| height | De hoogte van de rechthoek. Kan een double‑waarde of een tuple van double en LengthType zijn. |
| fill | De vulkleur of schilderstijl voor de rechthoek. Kan een Color of een Paint‑enumwaarde of een paint‑server‑ID zijn. Optionele parameter. |
| stroke | De lijnkleur of schilderstijl voor de omtrek van de rechthoek. Kan een Color of een Paint‑enumwaarde of een paint‑server‑ID zijn. Optionele parameter. |
| id | De unieke identifier voor het rechthoek‑element. Optionele parameter. |
| extend | Een optionele actie om de rechthoek‑element‑builder verder te configureren. |

### Retourwaarde

De builder‑instantie, waarmee method chaining mogelijk is.

### Zie ook

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
