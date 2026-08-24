---
title: "IXPathNSResolver 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.XPath.IXPathNSResolver 接口。XPathNSResolver 接口允许表达式中的前缀字符串正确绑定到 namespaceURI 字符串。IXPathEvaluator 可以从节点构建 IXPathNSResolver 的实现，或该接口可以由任何应用程序实现"
type: docs
weight: 3330
url: /zh/net/aspose.svg.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

`XPathNSResolver` 接口允许表达式中的 `prefix` 字符串正确绑定到 `namespaceURI` 字符串。[`IXPathEvaluator`](../ixpathevaluator/) 可以从节点构建 `IXPathNSResolver` 的实现，或该接口可以由任何应用程序实现。

```csharp
public interface IXPathNSResolver
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [LookupNamespaceURI](../../aspose.svg.dom.xpath/ixpathnsresolver/lookupnamespaceuri/)(*string*) | 查找与给定命名空间前缀关联的命名空间 URI。XPath 求值器绝不能使用 `null` 或空参数调用此方法，因为这样做的结果未定义。 |

### 另请参阅

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
