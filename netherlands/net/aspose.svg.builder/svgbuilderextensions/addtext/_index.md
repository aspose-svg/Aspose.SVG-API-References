---
title: "SVGBuilderExtensions.AddText"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddText-methode. Voegt een tekst‑elementconfiguratie toe aan de bouwer."
type: docs
weight: 530
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addtext/
---
## AddText<TBuilder>(*this TBuilder, Action&lt;SVGTextElementBuilder&gt;*) {#addtext}

Voegt een 'text' elementconfiguratie toe aan de builder.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, 
    Action<SVGTextElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | De configuratie‑actie voor het 'text'-element. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddText<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, FontStyle?, string, FontWeight?, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGTextElementBuilder&gt;*) {#addtext_1}

Voegt een 'text' element met opgegeven inhoud en attributen toe aan de SVG builder.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, string content, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> fontSize = null, FontStyle? fontStyle = default, 
    string fontFamily = null, FontWeight? fontWeight = default, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGTextElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbouwer, waarmee chaining mogelijk is. |
| builder | De bouwer‑instantie waaraan het 'text'-element zal worden toegevoegd. |
| inhoud | De tekstinhoud die moet worden weergegeven binnen het 'text'-element. |
| x | De x-coördinaat voor het tekst‑element. Kan een double‑waarde of een tuple van double en LengthType zijn. |
| y | De y-coördinaat voor het tekst‑element. Kan een double‑waarde of een tuple van double en LengthType zijn. |
| lettergrootte | De lettergrootte voor de tekst. Kan een double‑waarde of een tuple van double en LengthType zijn. |
| letterstijl | De letterstijl voor de tekst (bijv. normaal, cursief, schuin). |
| fontFamily | De lettertypefamilie voor de tekst (bijv., Arial, Verdana). |
| fontWeight | Het gewicht (dikte) van het lettertype (bijv., normaal, vet). |
| fill | De vulkleur of schilderstijl voor de tekst. Kan een Color of een Paint enum-waarde of een paint‑server‑ID zijn. |
| stroke | De lijnkleur of schilderstijl voor de tekst. Kan een Color of een Paint enum-waarde of een paint‑server‑ID zijn. |
| id | De unieke identifier voor het textelement. |
| extend | Een optionele actie om de tekst‑element‑bouwer verder te configureren. |

### Retourwaarde

De bouwer‑instantie voor het ketenen van verdere toevoegingen of configuraties.

### Zie ook

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [FontStyle](../../fontstyle/)
* enum [FontWeight](../../fontweight/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
