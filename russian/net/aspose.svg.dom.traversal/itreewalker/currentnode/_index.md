---
title: CurrentNode
second_title: Справочник по Aspose.SVG для .NET API
description: Узел в котором в данный момент находится TreeWalker. Изменения в дереве DOM могут привести к тому что текущий узел больше не будет приниматься соответствующим фильтром TreeWalker. currentNode также может быть явно задан для любого узла независимо от того находится ли он в поддереве заданном корневым узлом  или будет принят фильтром и whatToShow флаги. Дальнейший обход происходит относительно currentNode даже если он не является частью текущего представления путем применения фильтров в запрошенном направлении если обход невозможен то currentNode не изменяется.
type: docs
weight: 10
url: /ru/net/aspose.svg.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Узел, в котором в данный момент находится TreeWalker. Изменения в дереве DOM могут привести к тому, что текущий узел больше не будет приниматься соответствующим фильтром TreeWalker. currentNode также может быть явно задан для любого узла, независимо от того, находится ли он в поддереве, заданном корневым узлом , или будет принят фильтром и whatToShow флаги. Дальнейший обход происходит относительно currentNode, даже если он не является частью текущего представления, путем применения фильтров в запрошенном направлении; если обход невозможен, то currentNode не изменяется.

```csharp
public Node CurrentNode { get; set; }
```

### Стоимость имущества

Текущий узел.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception) | NOT_SUPPORTED_ERR: Возникает при попытке установить для currentNode значение null. |

### Смотрите также

* class [Node](../../../aspose.svg.dom/node)
* interface [ITreeWalker](../../itreewalker)
* пространство имен [Aspose.Svg.Dom.Traversal](../../itreewalker)
* сборка [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->