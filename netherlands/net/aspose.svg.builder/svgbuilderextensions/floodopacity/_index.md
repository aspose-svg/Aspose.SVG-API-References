---
title: "SVGBuilderExtensions.FloodOpacity"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions FloodOpacity-methode. Stelt het flood-opacity-attribuut in voor een SVG-element. Waarde moet tussen 0.0 volledig transparant en 1.0 volledig ondoorzichtig liggen."
type: docs
weight: 860
url: /nl/net/aspose.svg.builder/svgbuilderextensions/floodopacity/
---
## SVGBuilderExtensions.FloodOpacity<TBuilder> method

Stelt het 'flood-opacity' attribuut voor een SVG-element in. De waarde moet tussen 0,0 (volledig transparant) en 1,0 (volledig ondoorzichtig) liggen.

```csharp
public static TBuilder FloodOpacity<TBuilder>(this TBuilder builder, double opacity)
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
