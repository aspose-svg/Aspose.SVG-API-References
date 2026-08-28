---
title: "IXPathEvaluator.CreateExpression"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IXPathEvaluator CreateExpression メソッド。名前空間が解決された解析済み XPath 式を作成します。式がアプリケーションで再利用される場合に便利で、式文字列をより効率的な内部形式にコンパイルし、式内に現れるすべての名前空間プレフィックスを事前に解決できるようにします。"
type: docs
weight: 10
url: /ja/net/aspose.svg.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Creates a parsed XPath expression with resolved namespaces. This is useful when an expression will be reused in an application since it makes it possible to compile the expression string into a more efficient internal form and preresolve all namespace prefixes which occur within the expression.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 式 | String | 解析される XPath 式文字列です。 |
| resolver | IXPathNSResolver | `resolver` は、XPath 式内のすべてのプレフィックス（`xml` 名前空間プレフィックスを含む）を適切な名前空間 URI に変換できるようにします。これが `null` に指定された場合、式内の任意の名前空間プレフィックスは [`DOMException`](../../../aspose.svg.dom/domexception/) をスローし、コードは `NAMESPACE_ERR` になります。 |

### 戻り値

XPath 式のコンパイル済み形式です。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_EXPRESSION_ERR: 式が [`IXPathEvaluator`](../) の規則に従って合法でない場合に発生します。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | NAMESPACE_ERR: 指定された [`IXPathNSResolver`](../../ixpathnsresolver/) で解決できない名前空間プレフィックスを式が含む場合に発生します。 |

### 参照

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
