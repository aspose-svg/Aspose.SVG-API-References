---
title: "Node.CloneNode"
second_title: "Aspose.SVG for .NET API 参考"
description: "Node CloneNode 方法。返回调用此方法的节点的副本"
type: docs
weight: 180
url: /zh/net/aspose.svg.dom/node/clonenode/
---
## CloneNode() {#clonenode}

返回调用此方法的节点的副本。

克隆节点会复制其所有属性及其值，包括内在（内联）监听器。它不会复制使用 [`AddEventListener`](../../../aspose.svg.dom.events/ieventtarget/addeventlistener/) 添加的事件监听器或分配给元素属性的监听器（例如，node.onclick = someFunction）。此外，对于 HTMLCanvasElement 元素，绘制的图像不会被复制。

```csharp
public Node CloneNode()
```

### 返回值

新克隆的 [`Node`](../)。克隆的节点没有父节点，也不属于文档，直到使用 [`AppendChild`](../appendchild/) 或类似方法将其添加到文档中的另一个节点。

### 另请参阅

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CloneNode(*bool*) {#clonenode_1}

返回调用此方法的节点的副本。其参数决定是否同时克隆节点中包含的子树。

克隆节点会复制其所有属性及其值，包括内在（内联）监听器。它不会复制使用 [`AddEventListener`](../../../aspose.svg.dom.events/ieventtarget/addeventlistener/) 添加的事件监听器或分配给元素属性的监听器（例如，node.onclick = someFunction）。此外，对于 HTMLCanvasElement 元素，绘制的图像不会被复制。

```csharp
public Node CloneNode(bool deep)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| deep | Boolean | 如果为 true，则节点及其整个子树，包括子 [`Text`](../../text/) 节点中的文本，也会被复制。 |

### 返回值

新克隆的 [`Node`](../)。克隆的节点没有父节点，也不属于文档，直到使用 [`AppendChild`](../appendchild/) 或类似方法将其添加到文档中的另一个节点。

### 另请参阅

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
