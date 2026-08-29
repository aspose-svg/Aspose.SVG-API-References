---
title: "SVGBuilderExtensions.TextDecoration"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions TextDecoration-methode. Stelt het text-decoration‑attribuut in voor een SVG-element dat decoraties definieert die aan de tekst worden toegevoegd."
type: docs
weight: 2210
url: /nl/net/aspose.svg.builder/svgbuilderextensions/textdecoration/
---
## SVGBuilderExtensions.TextDecoration<TBuilder> method

Stelt het 'text-decoration' attribuut in voor een SVG-element, waarbij decoraties die aan de tekst worden toegevoegd worden gedefinieerd.

```csharp
public static TBuilder TextDecoration<TBuilder>(this TBuilder builder, bool underline = false, 
    bool overline = false, bool lineThrough = false, bool blink = false)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| underline | Specificeert of de tekst onderstreept moet worden. |
| overline | Specificeert of de tekst een overline moet hebben. |
| lineThrough | Specificeert of de tekst een doorstreping moet hebben. |
| knipperen | Specificeert of de tekst moet knipperen (niet aanbevolen voor gebruik). |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
