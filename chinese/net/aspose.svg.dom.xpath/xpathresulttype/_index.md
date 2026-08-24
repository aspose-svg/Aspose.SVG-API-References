---
title: "XPathResultType 枚举"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.XPath.XPathResultType 枚举。一个无符号短整数，指示此结果的类型。如果指定了特定类型，则结果将使用 XPath 类型转换（在需要且可能的情况下）返回为相应的类型。"
type: docs
weight: 3360
url: /zh/net/aspose.svg.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

一个无符号短整数，指示此结果的类型。如果指定了特定的 `type`，则结果将以相应的类型返回，并在需要和可能的情况下使用 XPath 类型转换。

```csharp
public enum XPathResultType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Any | `0` | 此代码不代表特定类型。对 XPath 表达式的求值永远不会产生此类型。如果请求此类型，则求值会返回表达式自然产生的任何类型。如果在请求 `Any` 类型时自然结果是节点集，则始终返回 `UnorderedNodeIterator` 类型。任何其他形式的节点集必须显式请求。 |
| Number | `1` | 结果是一个由 [XPath 1.0] 定义的数字。文档修改不会使该数字失效，但可能导致重新求值时得到的数字不同。 |
| String | `2` | 结果是一个由 [XPath 1.0] 定义的字符串。文档修改不会使该字符串失效，但可能导致该字符串不再对应当前文档。 |
| Boolean | `3` | 结果是一个由 [XPath 1.0] 定义的布尔值。文档修改不会使该布尔值失效，但可能导致重新求值时得到的布尔值不同。 |
| UnorderedNodeIterator | `4` | 结果是一个由 [XPath 1.0] 定义的节点集，将以迭代方式访问，可能不会按特定顺序产生节点。文档修改会使迭代失效。如果结果是节点集且请求 `Any` 类型，则返回此默认类型。 |
| OrderedNodeIterator | `5` | 结果是一个由 [XPath 1.0] 定义的节点集，将以迭代方式访问，产生文档顺序的节点。文档修改会使迭代失效。 |
| UnorderedNodeSnapshot | `6` | 结果是一个由 [XPath 1.0] 定义的节点集，将作为节点快照列表访问，节点可能不按特定顺序排列。文档修改不会使快照失效，但可能导致重新求值时快照不同，且快照中的节点可能已被修改、移动或从文档中删除。 |
| OrderedNodeSnapshot | `7` | 结果是一个由 [XPath 1.0] 定义的节点集，将作为节点快照列表访问，节点将保持原始文档顺序。文档修改不会使快照失效，但可能导致重新求值时快照不同，且快照中的节点可能已被修改、移动或从文档中删除。 |
| AnyUnorderedNode | `8` | 结果是一个由 [XPath 1.0] 定义的节点集，将作为单个节点访问，如果节点集为空，则可能为 `null`。文档修改不会使该节点失效，但可能导致结果节点不再对应当前文档。这是一种便利，可实现优化，因为实现可以在找到结果集中的任意节点后即停止。如果实际结果中有多个节点，返回的单个节点可能不是文档顺序中的第一个。 |
| FirstOrderedNode | `9` | 结果是由 [XPath 1.0] 定义的节点集，并将作为单个节点访问，如果节点集为空，则可能为 `null`。文档修改不会使节点失效，但可能导致结果节点不再对应当前文档。这是一种便利，可允许优化，因为实现可以在找到结果集中按文档顺序的第一个节点后停止。如果实际结果中有多个节点，返回的单个节点将是文档顺序中的第一个。 |

### 另请参阅

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
