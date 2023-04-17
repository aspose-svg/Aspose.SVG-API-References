---
title: IDocumentTraversal.CreateNodeIterator
second_title: Aspose.SVG für .NET-API-Referenz
description: IDocumentTraversal methode. Erstellen Sie einen neuen NodeIterator über dem Teilbaum der an dem angegebenen Knoten verwurzelt ist.
type: docs
weight: 10
url: /de/net/aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Erstellen Sie einen neuen NodeIterator über dem Teilbaum, der an dem angegebenen Knoten verwurzelt ist.

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| root | Node | Knoten, der zusammen mit seinen Kindern iteriert wird. Der Iterator steht zunächst direkt vor diesem Knoten. Die whatToShow-Flags und der Filter, sofern vorhanden, werden beim Setzen dieser Position nicht berücksichtigt. Die Wurzel darf nicht null sein. |

### Rückgabewert

Der neu erstellte NodeIterator.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn der angegebene Stamm null ist. |

### Siehe auch

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namensraum [Aspose.Svg.Dom.Traversal](../../idocumenttraversal/)
* Montage [Aspose.SVG](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Erstellen Sie einen neuen NodeIterator über dem Teilbaum, der an dem angegebenen Knoten verwurzelt ist.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| root | Node | Knoten, der zusammen mit seinen Kindern iteriert wird. Der Iterator steht zunächst direkt vor diesem Knoten. Die whatToShow-Flags und der Filter, sofern vorhanden, werden beim Setzen dieser Position nicht berücksichtigt. Die Wurzel darf nicht null sein. |
| whatToShow | Int64 | Flag gibt an, welche Knotentypen in der logischen Ansicht des vom Iterator präsentierten Baums erscheinen können. Siehe die Beschreibung von NodeFilter für den Satz möglicher SHOW_ Werte. Diese Flags können mit ODER kombiniert werden. |

### Rückgabewert

Der neu erstellte NodeIterator.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn der angegebene Stamm null ist. |

### Siehe auch

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namensraum [Aspose.Svg.Dom.Traversal](../../idocumenttraversal/)
* Montage [Aspose.SVG](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Erstellen Sie einen neuen NodeIterator über dem Teilbaum, der an dem angegebenen Knoten verwurzelt ist.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| root | Node | Knoten, der zusammen mit seinen Kindern iteriert wird. Der Iterator steht zunächst direkt vor diesem Knoten. Die whatToShow-Flags und der Filter, sofern vorhanden, werden beim Setzen dieser Position nicht berücksichtigt. Die Wurzel darf nicht null sein. |
| whatToShow | Int64 | Flag gibt an, welche Knotentypen in der logischen Ansicht des vom Iterator präsentierten Baums erscheinen können. Siehe die Beschreibung von NodeFilter für den Satz möglicher SHOW_ Werte. Diese Flags können mit ODER kombiniert werden. |
| filter | INodeFilter | NodeFilter, der mit this TreeWalker verwendet werden soll, oder null, um anzugeben, dass kein Filter vorhanden ist. |

### Rückgabewert

Der neu erstellte NodeIterator.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn der angegebene Stamm null ist. |

### Siehe auch

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* namensraum [Aspose.Svg.Dom.Traversal](../../idocumenttraversal/)
* Montage [Aspose.SVG](../../../)


