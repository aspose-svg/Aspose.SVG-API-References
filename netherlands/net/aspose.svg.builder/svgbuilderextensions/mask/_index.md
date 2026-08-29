---
title: "SVGBuilderExtensions.Mask"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGBuilderExtensions Mask methode. Stelt het mask‑attribuut in voor een SVG-element met behulp van een aangepaste mask‑configuratie."
type: docs
weight: 1150
url: /nl/net/aspose.svg.builder/svgbuilderextensions/mask/
---
## SVGBuilderExtensions.Mask<TBuilder> method

Stelt het 'mask' attribuut in voor een SVG-element met een aangepaste maskconfiguratie.

```csharp
public static TBuilder Mask<TBuilder>(this TBuilder builder, Action<MaskBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschrijving |
| --- | --- |
| TBuilder | Het type van de SVG-elementbuilder. |
| builder | De builder‑instantie. |
| configureren | Een delegate om de mask te configureren. |

### Retourwaarde

De builder‑instantie voor chaining.

### Zie ook

* class [MaskBuilder](../../maskbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
