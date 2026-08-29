---
title: "SVGBuilderExtensions.OnAbort"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions OnAbort methode. Stelt het onabort-eventattribuut in dat een script definieert dat moet worden uitgevoerd wanneer het laden van een SVG-document wordt afgebroken"
type: docs
weight: 1190
url: /nl/net/aspose.svg.builder/svgbuilderextensions/onabort/
---
## SVGBuilderExtensions.OnAbort<TBuilder> method

Stelt het 'onabort' gebeurtenisattribuut in, waarbij een script wordt gedefinieerd dat wordt uitgevoerd wanneer het laden van een SVG-document wordt afgebroken.

```csharp
public static TBuilder OnAbort<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentEventAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| waarde | De JavaScript-functie of het script dat moet worden uitgevoerd wanneer het laden van het document wordt afgebroken. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentEventAttributeSetter](../../idocumenteventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
