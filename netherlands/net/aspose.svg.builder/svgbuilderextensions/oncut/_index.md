---
title: "SVGBuilderExtensions.OnCut"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions OnCut-methode. Stelt het oncut‑evenementattribuut in dat een script definieert dat moet worden uitgevoerd wanneer inhoud uit het SVG-element wordt geknipt."
type: docs
weight: 1290
url: /nl/net/aspose.svg.builder/svgbuilderextensions/oncut/
---
## SVGBuilderExtensions.OnCut<TBuilder> method

Stelt het 'oncut' gebeurtenisattribuut in, waarbij een script wordt gedefinieerd dat wordt uitgevoerd wanneer inhoud wordt geknipt uit het SVG-element.

```csharp
public static TBuilder OnCut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| waarde | De JavaScript-functie of het script dat moet worden uitgevoerd bij het oncut‑evenement. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
