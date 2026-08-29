---
title: "SVGBuilderExtensions.OnCopy"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions OnCopy-methode. Stelt het oncopy‑evenementattribuut in dat een script definieert dat wordt uitgevoerd wanneer inhoud wordt gekopieerd vanuit het SVG‑element"
type: docs
weight: 1270
url: /nl/net/aspose.svg.builder/svgbuilderextensions/oncopy/
---
## SVGBuilderExtensions.OnCopy<TBuilder> method

Stelt het 'oncopy' gebeurtenisattribuut in, waarbij een script wordt gedefinieerd dat wordt uitgevoerd wanneer inhoud wordt gekopieerd vanuit het SVG-element.

```csharp
public static TBuilder OnCopy<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| waarde | De JavaScript-functie of het script dat moet worden uitgevoerd bij het kopieer‑evenement. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
