---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "INodeIterator PointerBeforeReferenceNode-Eigenschaft. Der Wert dieses Flags bestimmt, ob die Kinder von Entity-Referenzknoten für den Iterator sichtbar sind. Wenn false, werden sie und ihre Nachkommen verworfen. Beachten Sie, dass diese Ablehnung Vorrang vor whatToShow und dem Filter hat. Außerdem ist dies derzeit die einzige Situation, in der NodeIterators einen gesamten Teilbaum ablehnen können, anstatt einzelne Knoten zu überspringen. Um eine Ansicht des Dokuments zu erzeugen, bei der Entity-Referenzen expandiert sind und der Entity-Referenzknoten selbst nicht sichtbar ist, verwenden Sie die whatToShow-Flags, um den Entity-Referenzknoten zu verbergen, und setzen Sie expandEntityReferences beim Erzeugen des Iterators auf true. Um eine Ansicht zu erzeugen, bei der Entity-Referenzknoten vorhanden sind, aber keine Expansion erfolgt, verwenden Sie die whatToShow-Flags, um den Entity-Referenzknoten anzuzeigen, und setzen Sie expandEntityReferences auf false."
type: docs
weight: 10
url: /de/net/aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

Der Wert dieses Flags bestimmt, ob die Kinder von Entity-Reference‑Knoten für den Iterator sichtbar sind. Wenn false, werden sie und ihre Nachkommen abgelehnt. Beachten Sie, dass diese Ablehnung Vorrang vor whatToShow und dem Filter hat. Außerdem ist dies derzeit die einzige Situation, in der NodeIterators einen gesamten Teilbaum ablehnen können, anstatt einzelne Knoten zu überspringen. Um eine Ansicht des Dokuments zu erzeugen, in der Entity-References erweitert sind und der Entity-Reference‑Knoten selbst nicht sichtbar ist, verwenden Sie die whatToShow‑Flags, um den Entity-Reference‑Knoten zu verbergen, und setzen Sie expandEntityReferences beim Erstellen des Iterators auf true. Um eine Ansicht des Dokuments zu erzeugen, die Entity-Reference‑Knoten enthält, aber keine Entity‑Erweiterung, verwenden Sie die whatToShow‑Flags, um den Entity-Reference‑Knoten anzuzeigen, und setzen Sie expandEntityReferences auf false.

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` wenn [expand entity references]; andernfalls `false`.

### Siehe auch

* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
