---
title: "SVGBuilderExtensions.OnCut"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions OnCut Methode. Setzt das oncut-Attribut, das ein Skript definiert, das ausgeführt wird, wenn Inhalt aus dem SVG‑Element ausgeschnitten wird"
type: docs
weight: 1290
url: /de/net/aspose.svg.builder/svgbuilderextensions/oncut/
---
## SVGBuilderExtensions.OnCut<TBuilder> method

Setzt das Ereignisattribut 'oncut' und definiert ein Skript, das ausgeführt wird, wenn Inhalt aus dem SVG-Element ausgeschnitten wird.

```csharp
public static TBuilder OnCut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Die JavaScript‑Funktion oder das Skript, das beim Cut‑Ereignis ausgeführt wird. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
