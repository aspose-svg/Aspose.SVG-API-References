---
title: "IXPathResult.IterateNext"
second_title: "Aspose.SVG for .NET API 参考"
description: "IXPathResult IterateNext 方法。遍历并返回节点集中的下一个节点，如果没有更多节点则返回 null"
type: docs
weight: 80
url: /zh/net/aspose.svg.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

迭代并返回节点集中的下一个节点，如果没有更多节点则返回 `null`。

```csharp
public Node IterateNext()
```

### 返回值

返回下一个节点。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR：如果 `resultType` 不是 `UnorderedNodeIterator` 类型或 `OrderedNodeIterator` 类型则抛出。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR：自返回结果以来文档已被修改。 |

### 另请参阅

* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathResult](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
