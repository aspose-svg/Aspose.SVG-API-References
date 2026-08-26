---
title: "SVGBuilderExtensions.OnCopy"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions OnCopy-Methode. Legt das oncopy-Ereignisattribut fest, das ein Skript definiert, das ausgeführt wird, wenn Inhalt aus dem SVG-Element kopiert wird."
type: docs
weight: 1270
url: /de/net/aspose.svg.builder/svgbuilderextensions/oncopy/
---
## SVGBuilderExtensions.OnCopy<TBuilder> method

Setzt das Ereignisattribut 'oncopy' und definiert ein Skript, das ausgeführt wird, wenn Inhalt aus dem SVG-Element kopiert wird.

```csharp
public static TBuilder OnCopy<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Die JavaScript-Funktion oder das Skript, das beim Kopier-Ereignis ausgeführt wird. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
