---
title: "IElementTraversal‑Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Traversal.IElementTraversal‑Schnittstelle. Die ElementTraversal‑Schnittstelle ist ein Satz von schreibgeschützten Attributen, die es einem Autor ermöglichen, einfach zwischen Elementen in einem Dokument zu navigieren. In konformen Implementierungen von Element Traversal müssen alle Objekte, die Element implementieren, ebenfalls die ElementTraversal‑Schnittstelle implementieren."
type: docs
weight: 3230
url: /de/net/aspose.svg.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

The ElementTraversal interface is a set of read-only attributes which allow an author to easily navigate between elements in a document. In conforming implementations of Element Traversal, all objects that implement Element must also implement the ElementTraversal interface.

```csharp
public interface IElementTraversal
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ChildElementCount](../../aspose.svg.dom.traversal/ielementtraversal/childelementcount/) { get; } | Gibt die aktuelle Anzahl von Elementknoten zurück, die Kindknoten dieses Elements sind. 0, wenn dieses Element keine Kindknoten vom Knotentyp 1 hat. |
| [FirstElementChild](../../aspose.svg.dom.traversal/ielementtraversal/firstelementchild/) { get; } | Gibt den ersten Kind-Elementknoten dieses Elements zurück. null, wenn dieses Element keine Kindelemente hat. |
| [LastElementChild](../../aspose.svg.dom.traversal/ielementtraversal/lastelementchild/) { get; } | Gibt den letzten Kind-Elementknoten dieses Elements zurück. null, wenn dieses Element keine Kindelemente hat. |
| [NextElementSibling](../../aspose.svg.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | Gibt den nächsten Geschwister‑Elementknoten dieses Elements zurück. null, wenn dieses Element keine nachfolgenden Element‑Geschwisterknoten im Dokumentbaum hat. |
| [PreviousElementSibling](../../aspose.svg.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | Gibt den vorherigen Geschwister‑Elementknoten dieses Elements zurück. null, wenn dieses Element keine vorherigen Element‑Geschwisterknoten im Dokumentbaum hat. |

### Siehe auch

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
