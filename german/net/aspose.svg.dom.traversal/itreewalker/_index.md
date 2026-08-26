---
title: "ITreeWalker Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Traversal.ITreeWalker interface. TreeWalker-Objekte werden verwendet, um einen Dokumentbaum oder -unterbaum zu navigieren, wobei die Sicht des Dokuments verwendet wird, die durch ihre whatToShow-Flags und ggf. einen Filter definiert ist. Jede Funktion, die die Navigation mit einem TreeWalker durchführt, unterstützt automatisch jede durch einen TreeWalker definierte Sicht."
type: docs
weight: 3270
url: /de/net/aspose.svg.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker-Objekte werden verwendet, um einen Dokumentbaum oder Teilbaum zu navigieren, wobei die Ansicht des Dokuments verwendet wird, die durch ihre whatToShow-Flags und Filter (falls vorhanden) definiert ist. Jede Funktion, die die Navigation mit einem TreeWalker durchführt, unterstützt automatisch jede durch einen TreeWalker definierte Ansicht.

Das Auslassen von Knoten aus der logischen Ansicht eines Unterbaums kann zu einer Struktur führen, die wesentlich von demselben Unterbaum im vollständigen, ungefilterten Dokument abweicht. Knoten, die in der TreeWalker-Ansicht Geschwister sind, können in der ursprünglichen Ansicht Kinder verschiedener, weit auseinander liegender Knoten sein. Zum Beispiel betrachten Sie einen NodeFilter, der alle Knoten außer Textknoten und dem Wurzelknoten eines Dokuments überspringt. In der daraus resultierenden logischen Ansicht werden alle Textknoten Geschwister sein und als direkte Kinder des Wurzelknotens erscheinen, unabhängig davon, wie tief verschachtelt die Struktur des ursprünglichen Dokuments ist.

Siehe auch das [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface ITreeWalker : ITraversal
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CurrentNode](../../aspose.svg.dom.traversal/itreewalker/currentnode/) { get; set; } | Der Knoten, an dem der TreeWalker derzeit positioniert ist. Änderungen am DOM-Baum können dazu führen, dass der aktuelle Knoten nicht mehr vom zugehörigen Filter des TreeWalkers akzeptiert wird. currentNode kann auch explizit auf einen beliebigen Knoten gesetzt werden, unabhängig davon, ob er sich innerhalb des durch den Wurzelknoten angegebenen Unterbaums befindet oder vom Filter und den whatToShow-Flags akzeptiert würde. Weitere Traversierung erfolgt relativ zu currentNode, selbst wenn er nicht Teil der aktuellen Ansicht ist, indem die Filter in die gewünschte Richtung angewendet werden; ist keine Traversierung möglich, wird currentNode nicht geändert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FirstChild](../../aspose.svg.dom.traversal/itreewalker/firstchild/)() | Verschiebt den TreeWalker zum ersten sichtbaren Kind des aktuellen Knotens und gibt den neuen Knoten zurück. Hat der aktuelle Knoten keine sichtbaren Kinder, wird null zurückgegeben und der aktuelle Knoten bleibt erhalten. |
| [LastChild](../../aspose.svg.dom.traversal/itreewalker/lastchild/)() | Verschiebt den TreeWalker zum letzten sichtbaren Kind des aktuellen Knotens und gibt den neuen Knoten zurück. Hat der aktuelle Knoten keine sichtbaren Kinder, wird null zurückgegeben und der aktuelle Knoten bleibt erhalten. |
| [NextNode](../../aspose.svg.dom.traversal/itreewalker/nextnode/)() | Verschiebt den TreeWalker zum nächsten sichtbaren Knoten in Dokumentreihenfolge relativ zum aktuellen Knoten und gibt den neuen Knoten zurück. Wenn der aktuelle Knoten keinen nächsten Knoten hat oder wenn die Suche nach nextNode versucht, vom Wurzelknoten des TreeWalkers nach oben zu gehen, wird null zurückgegeben und der aktuelle Knoten bleibt erhalten. |
| [NextSibling](../../aspose.svg.dom.traversal/itreewalker/nextsibling/)() | Verschiebt den TreeWalker zum nächsten Geschwisterknoten des aktuellen Knotens und gibt den neuen Knoten zurück. Wenn der aktuelle Knoten kein sichtbares nächstes Geschwisterelement hat, wird null zurückgegeben und der aktuelle Knoten bleibt erhalten. |
| [ParentNode](../../aspose.svg.dom.traversal/itreewalker/parentnode/)() | Wechselt zum nächsten sichtbaren Vorgängerknoten des aktuellen Knotens und gibt ihn zurück. Wenn die Suche nach parentNode versucht, vom Wurzelknoten des TreeWalkers nach oben zu gehen, oder wenn kein sichtbarer Vorgängerknoten gefunden wird, behält diese Methode die aktuelle Position bei und gibt null zurück. |
| [PreviousNode](../../aspose.svg.dom.traversal/itreewalker/previousnode/)() | Verschiebt den TreeWalker zum vorherigen sichtbaren Knoten in Dokumentreihenfolge relativ zum aktuellen Knoten und gibt den neuen Knoten zurück. Wenn der aktuelle Knoten keinen vorherigen Knoten hat oder wenn die Suche nach previousNode versucht, vom Wurzelknoten des TreeWalkers nach oben zu gehen, wird null zurückgegeben und der aktuelle Knoten bleibt erhalten. |
| [PreviousSibling](../../aspose.svg.dom.traversal/itreewalker/previoussibling/)() | Verschiebt den TreeWalker zum vorherigen Geschwisterknoten des aktuellen Knotens und gibt den neuen Knoten zurück. Wenn der aktuelle Knoten kein sichtbares vorheriges Geschwisterelement hat, wird null zurückgegeben und der aktuelle Knoten bleibt erhalten. |

### Siehe auch

* interface [ITraversal](../itraversal/)
* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
