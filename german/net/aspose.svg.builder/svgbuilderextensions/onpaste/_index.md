---
title: "SVGBuilderExtensions.OnPaste"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions OnPaste-Methode. Setzt das onpaste-Event-Attribut, das ein Skript definiert, das ausgeführt wird, wenn Inhalt in das SVG-Element eingefügt wird."
type: docs
weight: 1640
url: /de/net/aspose.svg.builder/svgbuilderextensions/onpaste/
---
## SVGBuilderExtensions.OnPaste<TBuilder> method

Setzt das Attribut 'onpaste' und definiert ein Skript, das ausgeführt wird, wenn Inhalt in das SVG‑Element eingefügt wird.

```csharp
public static TBuilder OnPaste<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Die JavaScript-Funktion oder das Skript, das beim Paste-Ereignis ausgeführt wird. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
