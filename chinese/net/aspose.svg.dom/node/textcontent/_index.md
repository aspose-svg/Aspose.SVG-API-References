---
title: "Node.TextContent"
second_title: "Aspose.SVG for .NET API 参考"
description: "Node TextContent 属性。表示节点及其后代的文本内容"
type: docs
weight: 160
url: /zh/net/aspose.svg.dom/node/textcontent/
---
## Node.TextContent property

表示节点及其后代的文本内容。

```csharp
public virtual string TextContent { get; set; }
```

### Property Value

字符串或 null。其值取决于具体情况：

如果节点是文档或文档类型，`TextContent` 返回 null。注意：要获取整个文档的所有文本和 CDATA 数据，请使用

```csharp
document.DocumentElement.TextContent
```

.如果节点是 CDATA 区段、注释、处理指令或文本节点，`TextContent` 返回或设置节点内部的文本，即 [`NodeValue`](../nodevalue/)。对于其他节点类型，`TextContent` 返回所有子节点的 `TextContent` 的拼接，排除注释和处理指令。

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-textcontent).

### 另请参阅

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
