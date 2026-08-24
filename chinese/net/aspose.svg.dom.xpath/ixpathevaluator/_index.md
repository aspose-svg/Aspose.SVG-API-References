---
title: "IXPathEvaluator 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.XPath.IXPathEvaluator 接口。XPath 表达式的求值由 IXPathEvaluator 提供"
type: docs
weight: 3310
url: /zh/net/aspose.svg.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

XPath 表达式的求值由 `IXPathEvaluator` 提供。

```csharp
public interface IXPathEvaluator
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateExpression](../../aspose.svg.dom.xpath/ixpathevaluator/createexpression/)(*string, [IXPathNSResolver](../ixpathnsresolver/)*) | 创建一个已解析命名空间的 XPath 表达式。这在表达式将在应用程序中重复使用时很有用，因为它可以将表达式字符串编译为更高效的内部形式，并预先解析表达式中出现的所有命名空间前缀。 |
| [CreateNSResolver](../../aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/)(*[Node](../../aspose.svg.dom/node/)*) | 适配任何 DOM 节点以解析命名空间，从而可以相对于该节点在文档中出现的上下文轻松求值 XPath 表达式。此适配器的工作方式类似于 DOM Level 3 方法 `lookupNamespaceURI`，在节点上解析给定前缀的 namespaceURI，使用调用 lookupNamespaceURI 时节点层次结构中可用的当前信息，并且还能正确解析隐式的 xml 前缀。 |
| [Evaluate](../../aspose.svg.dom.xpath/ixpathevaluator/evaluate/)(*string, [Node](../../aspose.svg.dom/node/), [IXPathNSResolver](../ixpathnsresolver/), [XPathResultType](../xpathresulttype/), object*) | 求值 XPath 表达式字符串，并在可能的情况下返回指定类型的结果。 |

### 另请参阅

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
