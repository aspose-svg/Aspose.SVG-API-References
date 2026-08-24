---
title: "IXPathResult.SnapshotItem"
second_title: "Aspose.SVG for .NET API 参考"
description: "IXPathResult SnapshotItem 方法。返回快照集合中第 index 项。如果 index 大于或等于列表中节点的数量，则此方法返回 null。与迭代器结果不同，快照不会失效，但如果文档被修改，快照可能不再对应当前文档。"
type: docs
weight: 90
url: /zh/net/aspose.svg.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

返回快照集合中的第 `index` 项。如果 `index` 大于或等于列表中的节点数，则此方法返回 `null`。与迭代器结果不同，快照不会失效，但如果文档被修改，快照可能不再对应当前文档。

```csharp
public Node SnapshotItem(int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | Int32 | 快照集合的索引。 |

### 返回值

`NodeList` 中第 `index` 位的节点，如果该索引无效，则为 `null`。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: 如果 `resultType` 不是 `UnorderedNodeSnapshot` 类型或 `OrderedNodeSnapshot` 类型，则抛出。 |

### 另请参阅

* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathResult](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
