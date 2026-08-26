---
title: "SVGBuilderExtensions.AddContent"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions AddContent Methode. Fügt dem SVG‑Element Textinhalt hinzu"
type: docs
weight: 90
url: /de/net/aspose.svg.builder/svgbuilderextensions/addcontent/
---
## SVGBuilderExtensions.AddContent<TBuilder> method

Fügt dem SVG-Element Textinhalt hinzu.

```csharp
public static TBuilder AddContent<TBuilder>(this TBuilder builder, string text)
    where TBuilder : ISVGElementBuilder, ITextContentSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| Text | Der Text, der dem Element hinzugefügt werden soll. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

## Hinweise

Diese Methode ermöglicht das direkte Hinzufügen von Textinhalt zu einem SVG‑Element. Sie ist nützlich für Elemente, die textuelle Daten enthalten.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentSetter](../../itextcontentsetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
