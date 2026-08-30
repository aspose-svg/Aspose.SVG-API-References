---
title: "NodeList-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Collections.NodeList-klass. NodeList tillhandahåller abstraktionen av en ordnad samling av noder utan att definiera eller begränsa hur denna samling implementeras."
type: docs
weight: 2030
url: /sv/net/aspose.svg.collections/nodelist/
---
## NodeList class

NodeList tillhandahåller abstraktionen av en ordnad samling av noder, utan att definiera eller begränsa hur denna samling implementeras.

```csharp
public abstract class NodeList : DOMObject, IEnumerable<Node>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| abstract [Item](../../aspose.svg.collections/nodelist/item/) { get; } | Metoden returnerar det index‑te objektet i samlingen. Om index är större än eller lika med antalet noder i listan, returneras null. |
| abstract [Length](../../aspose.svg.collections/nodelist/length/) { get; } | Antalet noder i listan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| abstract [GetEnumerator](../../aspose.svg.collections/nodelist/getenumerator/)() | Returnerar en enumerator som itererar genom samlingen. |
| override [GetPlatformType](../../aspose.svg.collections/nodelist/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objekttyp. |

### Se även

* class [DOMObject](../../aspose.svg.dom/domobject/)
* class [Node](../../aspose.svg.dom/node/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
