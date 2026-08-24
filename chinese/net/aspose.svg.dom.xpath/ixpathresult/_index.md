---
title: "IXPathResult 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.XPath.IXPathResult 接口。XPathResult 接口表示在特定节点上下文中对 XPath 1.0 表达式求值的结果。由于 XPath 表达式的求值可能产生多种结果类型，此对象使得能够发现并操作结果的类型和值。"
type: docs
weight: 3350
url: /zh/net/aspose.svg.dom.xpath/ixpathresult/
---
## IXPathResult interface

`XPathResult` 接口表示在特定节点上下文中对 XPath 1.0 表达式求值的结果。由于 XPath 表达式的求值可能产生多种结果类型，此对象使得能够发现并操作结果的类型和值。

```csharp
public interface IXPathResult
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [BooleanValue](../../aspose.svg.dom.xpath/ixpathresult/booleanvalue/) { get; } | 此布尔结果的值。 |
| [InvalidIteratorState](../../aspose.svg.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | 表示迭代器已失效。如果 `resultType` 为 `UnorderedNodeIterator` 类型或 `OrderedNodeIterator` 类型，并且自返回此结果后文档已被修改，则为 true。 |
| [NumberValue](../../aspose.svg.dom.xpath/ixpathresult/numbervalue/) { get; } | 此数字结果的值。 |
| [ResultType](../../aspose.svg.dom.xpath/ixpathresult/resulttype/) { get; } | 一个表示此结果类型的代码，定义于 http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult [`XPathResultType`](../xpathresulttype/) 枚举。 |
| [SingleNodeValue](../../aspose.svg.dom.xpath/ixpathresult/singlenodevalue/) { get; } | 此单节点结果的值，可能为 `null`。 |
| [SnapshotLength](../../aspose.svg.dom.xpath/ixpathresult/snapshotlength/) { get; } | 结果快照中的节点数量。snapshotItem 索引的有效值为 `0` 到 `snapshotLength-1`（含）。 |
| [StringValue](../../aspose.svg.dom.xpath/ixpathresult/stringvalue/) { get; } | 此字符串结果的值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [IterateNext](../../aspose.svg.dom.xpath/ixpathresult/iteratenext/)() | 迭代并返回节点集中的下一个节点，如果没有更多节点则返回 `null`。 |
| [SnapshotItem](../../aspose.svg.dom.xpath/ixpathresult/snapshotitem/)(*int*) | 返回快照集合中的第 `index` 项。如果 `index` 大于或等于列表中的节点数，则此方法返回 `null`。与迭代器结果不同，快照不会失效，但如果文档被修改，快照可能不再对应当前文档。 |

### 另请参阅

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
