---
title: "INodeIterator Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Traversal.INodeIterator Schnittstelle. Iteratoren werden verwendet, um durch eine Menge von Knoten zu gehen, z. B. die Menge von Knoten in einer NodeList, das Dokumentunterbaum, der von einem bestimmten Node gesteuert wird, die Ergebnisse einer Abfrage oder jede andere Knotengruppe. Die zu iterierende Knotengruppe wird durch die Implementierung des NodeIterator bestimmt. DOM Level 2 spezifiziert eine einzelne NodeIterator‑Implementierung für die Dokumentreihenfolge‑Durchquerung eines Dokumentunterbaums. Instanzen dieser Iteratoren werden erzeugt, indem DocumentTraversal .createNodeIterator aufgerufen wird."
type: docs
weight: 3250
url: /de/net/aspose.svg.dom.traversal/inodeiterator/
---
## INodeIterator interface

Iteratoren werden verwendet, um durch eine Menge von Knoten zu gehen, z. B. die Menge von Knoten in einer NodeList, den Dokument-Teilbaum, der von einem bestimmten Node gesteuert wird, die Ergebnisse einer Abfrage oder jede andere Menge von Knoten. Die zu iterierende Knotenmengen wird durch die Implementierung des NodeIterator bestimmt. DOM Level 2 spezifiziert eine einzelne NodeIterator-Implementierung für die dokumentreihenfolge Traversierung eines Dokument-Teilbaums. Instanzen dieser Iteratoren werden erstellt, indem DocumentTraversal .createNodeIterator() aufgerufen wird.

Siehe auch das [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface INodeIterator : ITraversal
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | Der Wert dieses Flags bestimmt, ob die Kinder von Entity-Reference‑Knoten für den Iterator sichtbar sind. Wenn false, werden sie und ihre Nachkommen abgelehnt. Beachten Sie, dass diese Ablehnung Vorrang vor whatToShow und dem Filter hat. Außerdem ist dies derzeit die einzige Situation, in der NodeIterators einen gesamten Teilbaum ablehnen können, anstatt einzelne Knoten zu überspringen. Um eine Ansicht des Dokuments zu erzeugen, in der Entity-References erweitert sind und der Entity-Reference‑Knoten selbst nicht sichtbar ist, verwenden Sie die whatToShow‑Flags, um den Entity-Reference‑Knoten zu verbergen, und setzen Sie expandEntityReferences beim Erstellen des Iterators auf true. Um eine Ansicht des Dokuments zu erzeugen, die Entity-Reference‑Knoten enthält, aber keine Entity‑Erweiterung, verwenden Sie die whatToShow‑Flags, um den Entity-Reference‑Knoten anzuzeigen, und setzen Sie expandEntityReferences auf false. |
| [ReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/referencenode/) { get; } | Der aktuelle Referenzknoten. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Detach](../../aspose.svg.dom.traversal/inodeiterator/detach/)() | Löst den NodeIterator von der Menge, über die er iteriert hat, gibt alle Rechenressourcen frei und versetzt den Iterator in den Zustand INVALID. Nachdem detach aufgerufen wurde, führen Aufrufe von nextNode oder previousNode zur Ausnahme INVALID_STATE_ERR. |
| [NextNode](../../aspose.svg.dom.traversal/inodeiterator/nextnode/)() | Gibt den nächsten Knoten in der Menge zurück und verschiebt die Position des Iterators in der Menge nach vorne. Nachdem ein NodeIterator erstellt wurde, liefert der erste Aufruf von nextNode() den ersten Knoten in der Menge. |
| [PreviousNode](../../aspose.svg.dom.traversal/inodeiterator/previousnode/)() | Gibt den vorherigen Knoten in der Menge zurück und bewegt die Position des NodeIterators in der Menge rückwärts. |

### Siehe auch

* interface [ITraversal](../itraversal/)
* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
