---
title: "IDocumentTraversal.CreateTreeWalker"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод IDocumentTraversal CreateTreeWalker. Создает новый TreeWalker над поддеревом, корнем которого является указанный узел"
type: docs
weight: 20
url: /ru/net/aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/)*) {#createtreewalker}

Создайте новый TreeWalker над поддеревом, корневым в указанном узле.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| корень | Node | узел, который будет служить корнем для TreeWalker. Флаги whatToShow и NodeFilter не учитываются при установке этого значения; любой тип узла будет принят в качестве корня. currentNode TreeWalker инициализируется этим узлом, независимо от того, видим он или нет. Корень служит точкой остановки для методов обхода, которые поднимаются вверх по структуре документа, таких как parentNode и nextNode. Корень не должен быть null. |

### Возвращаемое значение

Недавно созданный TreeWalker.

### См. также

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/), long*) {#createtreewalker_1}

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

### См. также

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/), long, [INodeFilter](../../inodefilter/)*) {#createtreewalker_2}

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

### См. также

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
