---
title: "Document.CreateNodeIterator"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Document CreateNodeIterator-Methode. Erstellt einen neuen NodeIterator über den Teilbaum, der bei dem angegebenen Knoten wurzelt"
type: docs
weight: 900
url: /de/net/aspose.svg.dom/document/createnodeiterator/
---
## CreateNodeIterator(*[Node](../../node/)*) {#createnodeiterator}

Erstellt einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten wurzelt.

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| root | Node | Knoten, der zusammen mit seinen Kindern iteriert wird. Der Iterator ist zunächst direkt vor diesem Knoten positioniert. Die whatToShow-Flags und der Filter, falls vorhanden, werden bei der Festlegung dieser Position nicht berücksichtigt. Die Wurzel darf nicht null sein. |

### Rückgabewert

Der neu erstellte NodeIterator.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn die angegebene Wurzel null ist. |

### Siehe auch

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../node/), long*) {#createnodeiterator_1}

Erstellt einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten wurzelt.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| root | Node | Knoten, der zusammen mit seinen Kindern iteriert wird. Der Iterator ist zunächst direkt vor diesem Knoten positioniert. Die whatToShow-Flags und der Filter, falls vorhanden, werden bei der Festlegung dieser Position nicht berücksichtigt. Die Wurzel darf nicht null sein. |
| whatToShow | Int64 | Flag gibt an, welche Knotentypen in der logischen Ansicht des vom Iterator präsentierten Baums erscheinen dürfen. Siehe die Beschreibung von NodeFilter für die Menge möglicher SHOW_-Werte. Diese Flags können mit OR kombiniert werden. |

### Rückgabewert

Der neu erstellte NodeIterator.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn die angegebene Wurzel null ist. |

### Siehe auch

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../node/), long, [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)*) {#createnodeiterator_2}

Erstellt einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten wurzelt.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| root | Node | Knoten, der zusammen mit seinen Kindern iteriert wird. Der Iterator ist zunächst direkt vor diesem Knoten positioniert. Die whatToShow-Flags und der Filter, falls vorhanden, werden bei der Festlegung dieser Position nicht berücksichtigt. Die Wurzel darf nicht null sein. |
| whatToShow | Int64 | Flag gibt an, welche Knotentypen in der logischen Ansicht des vom Iterator präsentierten Baums erscheinen dürfen. Siehe die Beschreibung von NodeFilter für die Menge möglicher SHOW_-Werte. Diese Flags können mit OR kombiniert werden. |
| filter | INodeFilter | NodeFilter, der mit diesem TreeWalker verwendet werden soll, oder null, um keinen Filter anzugeben. |

### Rückgabewert

Der neu erstellte NodeIterator.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn die angegebene Wurzel null ist. |

### Siehe auch

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
