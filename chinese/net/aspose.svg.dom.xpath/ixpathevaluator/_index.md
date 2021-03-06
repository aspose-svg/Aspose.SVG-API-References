---
title: IXPathEvaluator
second_title: Aspose.SVG for .NET API 参考
description: XPath 表达式的求值由IXPathEvaluator./ixpathevaluator提供
type: docs
weight: 1320
url: /zh/net/aspose.svg.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

XPath 表达式的求值由[`IXPathEvaluator`](../ixpathevaluator)提供。

```csharp
public interface IXPathEvaluator
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CreateExpression](../../aspose.svg.dom.xpath/ixpathevaluator/createexpression)(string, IXPathNSResolver) | 使用已解析的命名空间创建已解析的 XPath 表达式。当表达式将在应用程序中重用时，这很有用 ，因为它可以使 将表达式字符串编译成更有效的内部形式，并且 可以预解析所有出现的命名空间前缀表达式内。 |
| [CreateNSResolver](../../aspose.svg.dom.xpath/ixpathevaluator/creatensresolver)(Node) | 调整任何 DOM 节点以解析名称空间，以便可以轻松地评估 XPath 表达式 相对于它在文档中出现的节点的上下文。这个适配器在使用节点的当前可用信息从给定前缀解析命名空间URI 时在节点上像DOM Level 3 方法` lookupNamespaceURI` 一样工作 。调用 lookupNamespaceURI 时的层次结构，也正确解析了隐式 xml 前缀。 |
| [Evaluate](../../aspose.svg.dom.xpath/ixpathevaluator/evaluate)(string, Node, IXPathNSResolver, XPathResultType, object) | 评估一个 XPath 表达式字符串，并尽可能返回指定类型的结果。 |

### 也可以看看

* 命名空间 [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath)
* 部件 [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
