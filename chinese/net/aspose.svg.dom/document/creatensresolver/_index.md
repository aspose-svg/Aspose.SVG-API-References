---
title: "Document.CreateNSResolver"
second_title: "Aspose.SVG for .NET API 参考"
description: "Document CreateNSResolver 方法。适配任何 DOM 节点以解析命名空间，使 XPath 表达式能够相对于出现该节点的文档上下文轻松评估。此适配器的工作方式类似于 DOM Level 3 方法 lookupNamespaceURI，在节点上解析给定前缀的 namespaceURI，使用在调用 lookupNamespaceURI 时节点层次结构中可用的当前信息，同时也正确解析隐式的 xml 前缀。"
type: docs
weight: 910
url: /zh/net/aspose.svg.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

适配任何 DOM 节点以解析命名空间，从而可以相对于该节点在文档中出现的上下文轻松求值 XPath 表达式。此适配器的工作方式类似于 DOM Level 3 方法 `lookupNamespaceURI`，在节点上解析给定前缀的 namespaceURI，使用调用 lookupNamespaceURI 时节点层次结构中可用的当前信息，并且还能正确解析隐式的 xml 前缀。

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nodeResolver | Node | 用于命名空间解析的上下文节点。 |

### 返回值

[`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver/) which resolves namespaces with respect to the definitions in scope for a specified node.

### 另请参阅

* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
