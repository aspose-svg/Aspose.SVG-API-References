---
title: "ITreeWalker.CurrentNode"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "ITreeWalker CurrentNode-Eigenschaft. Der Knoten, an dem der TreeWalker derzeit positioniert ist. Änderungen am DOM-Baum können dazu führen, dass der aktuelle Knoten vom zugehörigen Filter des TreeWalkers nicht mehr akzeptiert wird. currentNode kann auch explizit auf jeden beliebigen Knoten gesetzt werden, unabhängig davon, ob er sich innerhalb des vom Wurzelknoten angegebenen Teilbaums befindet oder vom Filter und den whatToShow-Flags akzeptiert würde. Weitere Traversierungen erfolgen relativ zu currentNode, selbst wenn er nicht Teil der aktuellen Ansicht ist, indem die Filter in der gewünschten Richtung angewendet werden; wenn keine Traversierung möglich ist, wird currentNode nicht geändert."
type: docs
weight: 10
url: /de/net/aspose.svg.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Der Knoten, an dem der TreeWalker derzeit positioniert ist. Änderungen am DOM-Baum können dazu führen, dass der aktuelle Knoten nicht mehr vom zugehörigen Filter des TreeWalkers akzeptiert wird. currentNode kann auch explizit auf einen beliebigen Knoten gesetzt werden, unabhängig davon, ob er sich innerhalb des durch den Wurzelknoten angegebenen Unterbaums befindet oder vom Filter und den whatToShow-Flags akzeptiert würde. Weitere Traversierung erfolgt relativ zu currentNode, selbst wenn er nicht Teil der aktuellen Ansicht ist, indem die Filter in die gewünschte Richtung angewendet werden; ist keine Traversierung möglich, wird currentNode nicht geändert.

```csharp
public Node CurrentNode { get; set; }
```

### Property Value

Der aktuelle Knoten.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn versucht wird, currentNode auf null zu setzen. |

### Siehe auch

* class [Node](../../../aspose.svg.dom/node/)
* interface [ITreeWalker](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
