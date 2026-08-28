---
title: "IXPathExpression.Evaluate"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IXPathExpression Evaluate メソッド。この XPath 式を評価し、結果を返します。"
type: docs
weight: 10
url: /ja/net/aspose.svg.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

この XPath 式を評価し、結果を返します。

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| contextNode | Node | `context` はこの XPath 式の評価のためのコンテキストノードです。[`IXPathEvaluator`](../../ixpathevaluator/) が [`Document`](../../../aspose.svg.dom/document/) をキャストして取得された場合、これは同じドキュメントに属し、[`Document`](../../../aspose.svg.dom/document/)、[`Element`](../../../aspose.svg.dom/element/)、[`Attr`](../../../aspose.svg.dom/attr/)、[`Text`](../../../aspose.svg.dom/text/)、[`CDATASection`](../../../aspose.svg.dom/cdatasection/)、[`Comment`](../../../aspose.svg.dom/comment/)、[`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction/)、または XPathNamespace ノードのいずれかでなければなりません。コンテキストノードが [`Text`](../../../aspose.svg.dom/text/) または [`CDATASection`](../../../aspose.svg.dom/cdatasection/) の場合、XPath が見る論理テキストノード全体として解釈されます。ただし、ノードが空の場合は XPath コンテキストとして使用できない場合があります。 |
| type | XPathResultType | 特定の `type` が指定された場合、結果は XPath の変換に依存して指定された型に強制変換され、望ましい変換が不可能な場合は失敗します。これは [`XPathResultType`](../../xpathresulttype/) のいずれかの値でなければなりません。 |
| result | Object | `result` はこのメソッドで再利用および返却される可能性のある特定の結果オブジェクトを指定します。`null` が指定された場合、または実装が指定された結果を再利用しない場合は、新しい結果オブジェクトが作成されて返されます。XPath 1.0 の結果の場合、このオブジェクトは [`IXPathResult`](../../ixpathresult/) 型になります。 |

### 戻り値

XPath 式の評価結果です。XPath 1.0 の結果の場合、このオブジェクトは [`IXPathResult`](../../ixpathresult/) 型になります。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: 結果を指定された型に変換できない場合に発生します。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | WRONG_DOCUMENT_ERR: ノードが、この [`IXPathExpression`](../) を作成した [`IXPathEvaluator`](../../ixpathevaluator/) でサポートされていないドキュメントからのものです。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: ノードが XPath コンテキストノードとして許可されたタイプではないか、要求されたタイプがこの [`IXPathExpression`](../) によって許可されていません。 |

### 参照

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.svg.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
