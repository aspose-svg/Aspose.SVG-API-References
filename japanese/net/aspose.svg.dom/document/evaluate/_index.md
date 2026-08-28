---
title: "Document.Evaluate"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Document Evaluate メソッド。XPath 式文字列を評価し、可能であれば指定された型の結果を返します。"
type: docs
weight: 950
url: /ja/net/aspose.svg.dom/document/evaluate/
---
## Document.Evaluate method

Evaluates an XPath expression string and returns a result of the specified type if possible.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 式 | String | 解析および評価される XPath 式文字列です。 |
| contextNode | ノード | この XPath 式の評価に使用されるコンテキストは、コンテキストノードです。 |
| リゾルバー | IXPathNSResolver | リゾルバーは、XML 名前空間プレフィックスを含むすべてのプレフィックスを、XPath 式内で適切な名前空間 URI に変換できるようにします。 |
| type | XPathResultType | 特定の型が指定された場合、結果は対応する型として返されます。 |
| result | オブジェクト | この結果は、再利用可能でこのメソッドが返す特定の結果オブジェクトを指定します。 |

### 戻り値

XPath式の評価結果。

### 参照

* interface [IXPathResult](../../../aspose.svg.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.svg.dom.xpath/xpathresulttype/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
