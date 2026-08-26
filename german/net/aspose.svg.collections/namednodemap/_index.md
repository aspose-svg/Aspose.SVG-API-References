---
title: "NamedNodeMap-Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Collections.NamedNodeMap-Klasse. Stellt Sammlungen von Attributen dar, die über ihren Namen zugänglich sind."
type: docs
weight: 2020
url: /de/net/aspose.svg.collections/namednodemap/
---
## NamedNodeMap class

Stellt Sammlungen von Attributen dar, die über ihren Namen zugänglich sind.

```csharp
public class NamedNodeMap : DOMObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Item](../../aspose.svg.collections/namednodemap/item/) { get; } | Gibt das Element an der Index‑Position in der Karte zurück. Wenn der Index größer oder gleich der Anzahl der Knoten in dieser Karte ist, wird null zurückgegeben. (2 Indexer) |
| [Length](../../aspose.svg.collections/namednodemap/length/) { get; } | Die Anzahl der Knoten in dieser Karte. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetNamedItem](../../aspose.svg.collections/namednodemap/getnameditem/)(*string*) | Ruft einen Knoten ab, der durch den Namen angegeben ist. |
| [GetNamedItemNS](../../aspose.svg.collections/namednodemap/getnameditemns/)(*string, string*) | Ruft einen Knoten ab, der durch lokalen Namen und Namespace-URI angegeben ist. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [RemoveNamedItem](../../aspose.svg.collections/namednodemap/removenameditem/)(*string*) | Entfernt einen Knoten, der durch den Namen angegeben ist. |
| [RemoveNamedItemNS](../../aspose.svg.collections/namednodemap/removenameditemns/)(*string, string*) | Entfernt einen Knoten, der durch lokalen Namen und Namespace-URI angegeben ist. |
| [SetNamedItem](../../aspose.svg.collections/namednodemap/setnameditem/)(*[Attr](../../aspose.svg.dom/attr/)*) | Fügt einen Knoten mithilfe seines nodeName-Attributs hinzu. Wenn bereits ein Knoten mit diesem Namen in dieser Zuordnung vorhanden ist, wird er durch den neuen ersetzt. Das Ersetzen eines Knotens durch sich selbst hat keine Wirkung. |
| [SetNamedItemNS](../../aspose.svg.collections/namednodemap/setnameditemns/)(*[Attr](../../aspose.svg.dom/attr/)*) | Fügt einen Knoten mithilfe seiner namespaceURI und seines localName hinzu. Wenn bereits ein Knoten mit dieser Namespace-URI und diesem lokalen Namen in dieser Zuordnung vorhanden ist, wird er durch den neuen ersetzt. Das Ersetzen eines Knotens durch sich selbst hat keine Wirkung. |

### Siehe auch

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
