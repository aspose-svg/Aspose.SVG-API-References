---
title: "SVGBuilderExtensions.FillOpacity"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions FillOpacity‑methode. Stelt het fill-opacity‑attribuut in voor een SVG‑element. De waarde moet tussen 0,0 (volledig transparant) en 1,0 (volledig ondoorzichtig) liggen."
type: docs
weight: 820
url: /nl/net/aspose.svg.builder/svgbuilderextensions/fillopacity/
---
## SVGBuilderExtensions.FillOpacity<TBuilder> method

Stelt het 'fill-opacity' attribuut in voor een SVG-element. De waarde moet tussen 0,0 (volledig transparant) en 1,0 (volledig ondoorzichtig) liggen.

```csharp
public static TBuilder FillOpacity<TBuilder>(this TBuilder builder, double opacity)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| opacity | De door te stellen opaciteitswaarde. |

### Retourwaarde

De builder‑instantie voor chaining.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| ArgumentOutOfRangeException | Wordt gegooid als de opaciteit niet binnen het geldige bereik valt. |

### Zie ook

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
