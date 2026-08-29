---
title: "ITreeWalker.CurrentNode"
second_title: "Aspose.SVG для .NET справочник API"
description: "Свойство ITreeWalker CurrentNode. Узел, в котором в данный момент находится TreeWalker. Изменения в дереве DOM могут привести к тому, что текущий узел больше не будет принят связанным с TreeWalker фильтром. currentNode также может быть явно установлен на любой узел, независимо от того, находится ли он в поддереве, определённом корневым узлом, или будет принят фильтром и флагами whatToShow. Последующая навигация происходит относительно currentNode, даже если он не является частью текущего представления, путём применения фильтров в запрошенном направлении; если навигация невозможна, currentNode не изменяется."
type: docs
weight: 10
url: /ru/net/aspose.svg.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Узел, в котором в данный момент находится TreeWalker. Изменения в дереве DOM могут привести к тому, что текущий узел больше не будет принят связанным с TreeWalker фильтром. currentNode также может быть явно установлен на любой узел, независимо от того, находится ли он в поддереве, указанном корневым узлом, или будет принят фильтром и флагами whatToShow. Дальнейший обход происходит относительно currentNode, даже если он не является частью текущего представления, применяя фильтры в запрошенном направлении; если обход невозможен, currentNode не изменяется.

```csharp
public Node CurrentNode { get; set; }
```

### Property Value

Текущий узел.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Возникает, если попытаться установить currentNode в null. |

### См. также

* class [Node](../../../aspose.svg.dom/node/)
* interface [ITreeWalker](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
