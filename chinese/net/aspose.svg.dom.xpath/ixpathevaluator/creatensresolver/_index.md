---
title: "IXPathEvaluator.CreateNSResolver"
second_title: "Aspose.SVG for .NET API 参考"
description: "IXPathEvaluator CreateNSResolver 方法。将任意 DOM 节点适配为能够解析命名空间，以便可以相对于该节点在文档中出现的上下文轻松评估 XPath 表达式。此适配器的工作方式类似于 DOM Level 3 中节点的 lookupNamespaceURI 方法，它使用调用时节点层次结构中可用的当前信息来根据给定前缀解析 namespaceURI，并且还能正确解析隐式的 xml 前缀。"
type: docs
weight: 20
url: /zh/net/aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

适配任何 DOM 节点以解析命名空间，从而可以相对于该节点在文档中出现的上下文轻松求值 XPath 表达式。此适配器的工作方式类似于 DOM Level 3 方法 `lookupNamespaceURI`，在节点上解析给定前缀的 namespaceURI，使用调用 lookupNamespaceURI 时节点层次结构中可用的当前信息，并且还能正确解析隐式的 xml 前缀。

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nodeResolver | Node | 用于命名空间解析的上下文节点。 |

### 返回值

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves namespaces with respect to the definitions in scope for a specified node.

### 另请参阅

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
