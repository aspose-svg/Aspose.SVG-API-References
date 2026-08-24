---
title: "IParentNode 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.IParentNode 接口。定义了任何可能的父对象实现的 IParentNode 接口"
type: docs
weight: 3080
url: /zh/net/aspose.svg.dom/iparentnode/
---
## IParentNode interface

定义 `IParentNode` 接口，该接口由任何可能的父对象实现。

```csharp
public interface IParentNode : IElementTraversal
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ChildElementCount](../../aspose.svg.dom/iparentnode/childelementcount/) { get; } | childElementCount 属性必须返回上下文对象中作为元素的子节点数量。 |
| [Children](../../aspose.svg.dom/iparentnode/children/) { get; } | 返回子元素。 |
| [FirstElementChild](../../aspose.svg.dom/iparentnode/firstelementchild/) { get; } | 返回第一个是元素的子节点，否则返回 null。 |
| [LastElementChild](../../aspose.svg.dom/iparentnode/lastelementchild/) { get; } | 返回最后一个是元素的子节点，否则返回 null。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [QuerySelector](../../aspose.svg.dom/iparentnode/queryselector/)(*string*) | 返回匹配选择器的节点的第一个后代元素。 |
| [QuerySelectorAll](../../aspose.svg.dom/iparentnode/queryselectorall/)(*string*) | 返回匹配选择器的节点的所有元素后代。 |

### 另请参阅

* interface [IElementTraversal](../../aspose.svg.dom.traversal/ielementtraversal/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
