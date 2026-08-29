---
title: "SVGBuilderExtensions.AddLine"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddLine-methode. Voegt een lijn‑elementconfiguratie toe aan de builder."
type: docs
weight: 350
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addline/
---
## AddLine<TBuilder>(*this TBuilder, Action&lt;SVGLineElementBuilder&gt;*) {#addline_1}

Voegt een 'line'-elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    Action<SVGLineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'line'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLine<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGLineElementBuilder&gt;*) {#addline}

Voegt een 'line'-element met opgegeven begin- en eindpunten, en stijlen toe aan de SVG-builder.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1 = null, OneOf<double, (double, LengthType)> y1 = null, 
    OneOf<double, (double, LengthType)> x2 = null, OneOf<double, (double, LengthType)> y2 = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGLineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder, dat vloeiend API-gebruik mogelijk maakt. |
| builder | De SVG‑builder‑instantie waaraan het 'line'-element zal worden toegevoegd. |
| x1 | De x-coördinaat van het startpunt van de lijn. Kan een double‑waarde of een tuple van double en LengthType zijn. |
| y1 | De y-coördinaat van het startpunt van de lijn. Kan een double‑waarde of een tuple van double en LengthType zijn. |
| x2 | De x-coördinaat van het eindpunt van de lijn. Kan een double‑waarde of een tuple van double en LengthType zijn. |
| y2 | De y-coördinaat van het eindpunt van de lijn. Kan een double‑waarde of een tuple van double en LengthType zijn. |
| fill | De vulkleur of schilderstijl voor de lijn. Kan een Color‑ of Paint‑enumwaarde of een paint‑server‑ID zijn. Optionele parameter. |
| stroke | De lijnkleur of schilderstijl voor de lijn. Kan een Color‑ of Paint‑enumwaarde of een paint‑server‑ID zijn. Optionele parameter. |
| id | De unieke identifier voor het lijn‑element. Optionele parameter. |
| extend | Een optionele actie om de lijn‑element‑builder verder te configureren. |

### Retourwaarde

De builder‑instantie, waarmee method chaining mogelijk is.

### Zie ook

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
