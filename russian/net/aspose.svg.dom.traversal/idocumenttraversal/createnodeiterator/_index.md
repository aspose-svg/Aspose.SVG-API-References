---
title: "IDocumentTraversal.CreateNodeIterator"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод IDocumentTraversal CreateNodeIterator. Создает новый NodeIterator над поддеревом, корнем которого является указанный узел"
type: docs
weight: 10
url: /ru/net/aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(*[Node](../../../aspose.svg.dom/node/)*) {#createnodeiterator}

Создаёт новый NodeIterator для поддерева, корнем которого является указанный узел.

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| корень | Node | узел, который будет итеративно обрабатываться вместе со своими дочерними элементами. Итератор изначально позиционируется непосредственно перед этим узлом. Флаги whatToShow и фильтр, если они заданы, не учитываются при установке этой позиции. Корень не должен быть null. |

### Возвращаемое значение

Новый созданный NodeIterator.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень равен null. |

### См. также

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../../aspose.svg.dom/node/), long*) {#createnodeiterator_1}

Создаёт новый NodeIterator для поддерева, корнем которого является указанный узел.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| корень | Node | узел, который будет итеративно обрабатываться вместе со своими дочерними элементами. Итератор изначально позиционируется непосредственно перед этим узлом. Флаги whatToShow и фильтр, если они заданы, не учитываются при установке этой позиции. Корень не должен быть null. |
| whatToShow | Int64 | флаг указывает, какие типы узлов могут появляться в логическом представлении дерева, предоставляемого итератором. См. описание NodeFilter для набора возможных значений SHOW_. Эти флаги можно комбинировать с помощью OR. |

### Возвращаемое значение

Новый созданный NodeIterator.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень равен null. |

### См. также

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../../aspose.svg.dom/node/), long, [INodeFilter](../../inodefilter/)*) {#createnodeiterator_2}

Создаёт новый NodeIterator для поддерева, корнем которого является указанный узел.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| корень | Node | узел, который будет итеративно обрабатываться вместе со своими дочерними элементами. Итератор изначально позиционируется непосредственно перед этим узлом. Флаги whatToShow и фильтр, если они заданы, не учитываются при установке этой позиции. Корень не должен быть null. |
| whatToShow | Int64 | флаг указывает, какие типы узлов могут появляться в логическом представлении дерева, предоставляемого итератором. См. описание NodeFilter для набора возможных значений SHOW_. Эти флаги можно комбинировать с помощью OR. |
| filter | INodeFilter | NodeFilter, используемый с этим TreeWalker, или null, указывающий отсутствие фильтра. |

### Возвращаемое значение

Новый созданный NodeIterator.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень равен null. |

### См. также

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
