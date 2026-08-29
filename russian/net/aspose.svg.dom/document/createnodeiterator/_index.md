---
title: "Document.CreateNodeIterator"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Document CreateNodeIterator. Создает новый NodeIterator над поддеревом, корнем которого является указанный узел"
type: docs
weight: 900
url: /ru/net/aspose.svg.dom/document/createnodeiterator/
---
## CreateNodeIterator(*[Node](../../node/)*) {#createnodeiterator}

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
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень равен null. |

### См. также

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../node/), long*) {#createnodeiterator_1}

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
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень равен null. |

### См. также

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../node/), long, [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)*) {#createnodeiterator_2}

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
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень равен null. |

### См. также

* interface [INodeIterator](../../../aspose.svg.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
