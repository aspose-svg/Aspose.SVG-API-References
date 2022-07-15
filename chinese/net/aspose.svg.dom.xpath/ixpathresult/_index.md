---
title: IXPathResult
second_title: Aspose.SVG for .NET API 参考
description:  XPathResult 接口表示在特定节点的上下文中计算 XPath 1.0 表达式的结果由于对 XPath 表达式的求值 可以产生各种结果类型因此该对象使 可以发现和操作结果的类型和值
type: docs
weight: 1360
url: /zh/net/aspose.svg.dom.xpath/ixpathresult/
---
## IXPathResult interface

` XPathResult` 接口表示在特定节点的上下文中计算 XPath 1.0 表达式的结果。由于对 XPath 表达式的求值 可以产生各种结果类型，因此该对象使 可以发现和操作结果的类型和值。

```csharp
public interface IXPathResult
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BooleanValue](../../aspose.svg.dom.xpath/ixpathresult/booleanvalue) { get; } | 这个布尔结果的值。 |
| [InvalidIteratorState](../../aspose.svg.dom.xpath/ixpathresult/invaliditeratorstate) { get; } | 表示迭代器已经失效。如果` resultType` 为` UnorderedNodeIterator` 类型或` OrderedNodeIterator` 类型，则为真并且 自从返回此结果以来，该文档已被修改。 |
| [NumberValue](../../aspose.svg.dom.xpath/ixpathresult/numbervalue) { get; } | 这个数字结果的值。 |
| [ResultType](../../aspose.svg.dom.xpath/ixpathresult/resulttype) { get; } | 表示此结果类型的代码，由 http://www.w3.org/TR/DOM-Level-3-XPath/xpath 定义.html#XPathResult [`XPathResultType`](../xpathresulttype)枚举。 |
| [SingleNodeValue](../../aspose.svg.dom.xpath/ixpathresult/singlenodevalue) { get; } | 这个单节点结果的值，可能是 `null`. |
| [SnapshotLength](../../aspose.svg.dom.xpath/ixpathresult/snapshotlength) { get; } | 结果快照中的节点数。 snapshotItem 的有效值 指数是 `0` 至 `快照长度-1` 包括的。 |
| [StringValue](../../aspose.svg.dom.xpath/ixpathresult/stringvalue) { get; } | 此字符串结果的值。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [IterateNext](../../aspose.svg.dom.xpath/ixpathresult/iteratenext)() | 迭代并返回节点集中的下一个节点或 `null` 如果没有更多的节点。 |
| [SnapshotItem](../../aspose.svg.dom.xpath/ixpathresult/snapshotitem)(int) | 返回 `指数`快照集合中的项目。 如果 `指数` 大于 或等于列表中的节点数，此方法返回 `null`. 不像 迭代器结果，快照不会失效，但可能与当前不对应 如果它发生突变，请记录。 |

### 也可以看看

* 命名空间 [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath)
* 部件 [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->