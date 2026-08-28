---
title: "IXPathEvaluator.Evaluate"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IXPathEvaluator Evaluate メソッド。XPath 式文字列を評価し、可能であれば指定された型の結果を返します。"
type: docs
weight: 30
url: /ja/net/aspose.svg.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Evaluates an XPath expression string and returns a result of the specified type if possible.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 式 | String | 解析および評価される XPath 式文字列です。 |
| contextNode | Node | `context` はこの XPath 式の評価のためのコンテキストノードです。[`IXPathEvaluator`](../) が [`Document`](../../../aspose.svg.dom/document/) をキャストして取得された場合、これは同じドキュメントが所有し、[`Document`](../../../aspose.svg.dom/document/)、[`Element`](../../../aspose.svg.dom/element/)、[`Attr`](../../../aspose.svg.dom/attr/)、[`Text`](../../../aspose.svg.dom/text/)、[`CDATASection`](../../../aspose.svg.dom/cdatasection/)、[`Comment`](../../../aspose.svg.dom/comment/)、[`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction/)、または XPathNamespace ノードのいずれかでなければなりません。コンテキストノードが [`Text`](../../../aspose.svg.dom/text/) または [`CDATASection`](../../../aspose.svg.dom/cdatasection/) の場合、XPath が見る論理テキストノード全体として解釈されます。ただし、ノードが空の場合は XPath コンテキストとして使用できません。 |
| resolver | IXPathNSResolver | `resolver` は、XPath 式内のすべてのプレフィックス（`xml` 名前空間プレフィックスを含む）を適切な名前空間 URI に変換できるようにします。これが `null` に指定された場合、式内の任意の名前空間プレフィックスは [`DOMException`](../../../aspose.svg.dom/domexception/) をスローし、コードは `NAMESPACE_ERR` になります。 |
| type | XPathResultType | 特定の `type` が指定された場合、結果は対応する型で返されます。XPath 1.0 の結果については、[`XPathResultType`](../../xpathresulttype/) 列挙型のいずれかの値でなければなりません。 |
| result | Object | `result` はこのメソッドで再利用および返却される可能性のある特定の結果オブジェクトを指定します。`null` が指定された場合、または実装が指定された結果を再利用しない場合は、新しい結果オブジェクトが作成されて返されます。XPath 1.0 の結果の場合、このオブジェクトは [`IXPathResult`](../../ixpathresult/) 型になります。 |

### 戻り値

XPath 式の評価結果です。XPath 1.0 の結果の場合、このオブジェクトは [`IXPathResult`](../../ixpathresult/) 型になります。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_EXPRESSION_ERR: 式が [`IXPathEvaluator`](../) の規則に従って合法でない場合に発生します。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: 結果を指定された型に変換できない場合に発生します。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | NAMESPACE_ERR: 指定された [`IXPathNSResolver`](../../ixpathnsresolver/) で解決できない名前空間プレフィックスを式が含む場合に発生します。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | WRONG_DOCUMENT_ERR: ノードがこの [`IXPathEvaluator`](../) でサポートされていないドキュメントからのものです。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: ノードが XPath コンテキストノードとして許可されたタイプではないか、要求されたタイプがこの [`IXPathEvaluator`](../) によって許可されていません。 |

### 参照

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
