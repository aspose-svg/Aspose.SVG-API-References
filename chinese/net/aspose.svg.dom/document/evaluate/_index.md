---
title: "Document.Evaluate"
second_title: "Aspose.SVG for .NET API 参考"
description: "Document Evaluate 方法。评估 XPath 表达式字符串，并在可能的情况下返回指定类型的结果"
type: docs
weight: 950
url: /zh/net/aspose.svg.dom/document/evaluate/
---
## Document.Evaluate method

求值 XPath 表达式字符串，并在可能的情况下返回指定类型的结果。

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| expression | String | 待解析和评估的 XPath 表达式字符串。 |
| contextNode | Node | 上下文是此 XPath 表达式求值的上下文节点。 |
| resolver | IXPathNSResolver | 解析器允许将 XPath 表达式中的所有前缀（包括 xml 命名空间前缀）转换为相应的命名空间 URI。 |
| type | XPathResultType | 如果指定了特定类型，则结果将以相应的类型返回。 |
| result | 对象 | 该结果指定了一个特定的结果对象，可被此方法复用并返回。 |

### 返回值

XPath 表达式求值的结果。

### 另请参阅

* interface [IXPathResult](../../../aspose.svg.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.svg.dom.xpath/xpathresulttype/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
