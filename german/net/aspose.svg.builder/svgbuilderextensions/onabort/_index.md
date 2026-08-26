---
title: "SVGBuilderExtensions.OnAbort"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Methode SVGBuilderExtensions OnAbort. Setzt das onabort-Ereignisattribut, das ein Skript definiert, das ausgeführt wird, wenn das Laden eines SVG-Dokuments abgebrochen wird."
type: docs
weight: 1190
url: /de/net/aspose.svg.builder/svgbuilderextensions/onabort/
---
## SVGBuilderExtensions.OnAbort<TBuilder> method

Setzt das Ereignisattribut 'onabort' und definiert ein Skript, das ausgeführt wird, wenn das Laden eines SVG-Dokuments abgebrochen wird.

```csharp
public static TBuilder OnAbort<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentEventAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Die JavaScript-Funktion oder das Skript, das ausgeführt wird, wenn das Laden des Dokuments abgebrochen wird. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentEventAttributeSetter](../../idocumenteventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
