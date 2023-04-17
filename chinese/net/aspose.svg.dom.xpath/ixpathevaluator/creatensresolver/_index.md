---
title: IXPathEvaluator.CreateNSResolver
second_title: Aspose.SVG for .NET API 参考
description: IXPathEvaluator 方法. 调整任何 DOM 节点以解析名称空间以便可以相对于它在文档中出现的节点的上下文轻松地评估 XPath 表达式 这个适配器像 DOM Level 3 方法一样工作 查找命名空间URI在调用 time lookupNamespaceURI 时使用节点层次结构中可用的当前信息从给定前缀解析 namespaceURI 的节点上还正确解析隐式 xml 前缀.
type: docs
weight: 20
url: /zh/net/aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

调整任何 DOM 节点以解析名称空间，以便可以相对于它在文档中出现的节点的上下文轻松地评估 XPath 表达式 。这个适配器像 DOM Level 3 方法一样工作 `查找命名空间URI`在调用 time lookupNamespaceURI 时使用节点层次结构中可用的当前信息从给定前缀解析 namespaceURI 的节点上，还正确解析隐式 xml 前缀.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| nodeResolver | Node | 用作命名空间解析上下文的节点。 |

### 返回值

[`IXPathNSResolver`](../../ixpathnsresolver/)它在指定节点的范围内解析关于 definitions 的命名空间。

### 也可以看看

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathEvaluator](../)
* 命名空间 [Aspose.Svg.Dom.XPath](../../ixpathevaluator/)
* 部件 [Aspose.SVG](../../../)


