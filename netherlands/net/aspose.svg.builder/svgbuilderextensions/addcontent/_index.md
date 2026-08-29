---
title: "SVGBuilderExtensions.AddContent"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions AddContent-methode. Voegt tekstinhoud toe aan het SVG-element."
type: docs
weight: 90
url: /nl/net/aspose.svg.builder/svgbuilderextensions/addcontent/
---
## SVGBuilderExtensions.AddContent<TBuilder> method

Voegt tekstinhoud toe aan het SVG‑element.

```csharp
public static TBuilder AddContent<TBuilder>(this TBuilder builder, string text)
    where TBuilder : ISVGElementBuilder, ITextContentSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De SVG-elementbuilder. |
| tekst | De tekst die aan het element moet worden toegevoegd. |

### Retourwaarde

De builder‑instantie voor chaining.

## Opmerkingen

Deze methode maakt het mogelijk om tekstinhoud direct aan een SVG-element toe te voegen. Het is handig voor elementen die tekstuele gegevens bevatten.

### Zie ook

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentSetter](../../itextcontentsetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
