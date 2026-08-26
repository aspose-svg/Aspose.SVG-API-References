---
title: "SVGBuilderExtensions.OnUnload"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions OnUnload-Methode. Setzt das onunload-Ereignisattribut, das ein Skript definiert, das ausgeführt wird, wenn das SVG-Dokument entladen wird."
type: docs
weight: 1830
url: /de/net/aspose.svg.builder/svgbuilderextensions/onunload/
---
## SVGBuilderExtensions.OnUnload<TBuilder> method

Setzt das Attribut 'onunload' und definiert ein Skript, das ausgeführt wird, wenn das SVG‑Dokument entladen wird.

```csharp
public static TBuilder OnUnload<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentEventAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Die JavaScript-Funktion oder das Skript, das ausgeführt wird, wenn das Dokument entladen wird. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentEventAttributeSetter](../../idocumenteventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
