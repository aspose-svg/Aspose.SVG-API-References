---
title: "Document.CreateTreeWalker"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Document CreateTreeWalker. Создаёт новый TreeWalker над поддеревом, корнем которого является указанный узел."
type: docs
weight: 940
url: /ru/net/aspose.svg.dom/document/createtreewalker/
---
## CreateTreeWalker(*[Node](../../node/)*) {#createtreewalker}

Создайте новый TreeWalker над поддеревом, корневым в указанном узле.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| корень | Node | узел, который будет служить корнем для TreeWalker. Флаги whatToShow и NodeFilter не учитываются при установке этого значения; любой тип узла будет принят в качестве корня. currentNode TreeWalker инициализируется этим узлом, независимо от того, видим он или нет. Корень служит точкой остановки для методов обхода, которые поднимаются вверх по структуре документа, таких как parentNode и nextNode. Корень не должен быть null. |

### Возвращаемое значение

Недавно созданный TreeWalker.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень равен null. |

### См. также

* interface [ITreeWalker](../../../aspose.svg.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../node/), long*) {#createtreewalker_1}

Создайте новый TreeWalker над поддеревом, корневым в указанном узле.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| корень | Node | узел, который будет служить корнем для TreeWalker. Флаги whatToShow и NodeFilter не учитываются при установке этого значения; любой тип узла будет принят в качестве корня. currentNode TreeWalker инициализируется этим узлом, независимо от того, видим он или нет. Корень служит точкой остановки для методов обхода, которые поднимаются вверх по структуре документа, таких как parentNode и nextNode. Корень не должен быть null. |
| whatToShow | Int64 | Флаг указывает, какие типы узлов могут появляться в логическом представлении дерева, представленного tree-walker‑ом. См. описание NodeFilter для набора возможных значений SHOW_. Эти флаги можно комбинировать с помощью OR. |

### Возвращаемое значение

Недавно созданный TreeWalker.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень равен null. |

### См. также

* interface [ITreeWalker](../../../aspose.svg.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../node/), long, [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)*) {#createtreewalker_2}

Создайте новый TreeWalker над поддеревом, корневым в указанном узле.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| корень | Node | узел, который будет служить корнем для TreeWalker. Флаги whatToShow и NodeFilter не учитываются при установке этого значения; любой тип узла будет принят в качестве корня. currentNode TreeWalker инициализируется этим узлом, независимо от того, видим он или нет. Корень служит точкой остановки для методов обхода, которые поднимаются вверх по структуре документа, таких как parentNode и nextNode. Корень не должен быть null. |
| whatToShow | Int64 | Флаг указывает, какие типы узлов могут появляться в логическом представлении дерева, представленного tree-walker‑ом. См. описание NodeFilter для набора возможных значений SHOW_. Эти флаги можно комбинировать с помощью OR. |
| filter | INodeFilter | NodeFilter, используемый с этим TreeWalker, или null, указывающий отсутствие фильтра. |

### Возвращаемое значение

Недавно созданный TreeWalker.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Возникает, если указанный корень равен null. |

### См. также

* interface [ITreeWalker](../../../aspose.svg.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
