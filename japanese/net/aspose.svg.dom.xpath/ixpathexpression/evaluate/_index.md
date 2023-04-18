---
title: IXPathExpression.Evaluate
second_title: Aspose.SVG for .NET API リファレンス
description: IXPathExpression 方法. この XPath 式を評価し結果を返します
type: docs
weight: 10
url: /ja/net/aspose.svg.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

この XPath 式を評価し、結果を返します。

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| contextNode | Node | の`コンテクスト`この XPath 式を評価するためのコンテキスト ノードです。 [`IXPathEvaluator`](../../ixpathevaluator/)キャストすることによって得られた[`Document`](../../../aspose.svg.dom/document/)次に、これは同じドキュメントが所有する でなければならず、[`Document`](../../../aspose.svg.dom/document/)、[`Element`](../../../aspose.svg.dom/element/)、[`Attr`](../../../aspose.svg.dom/attr/)、 [`Text`](../../../aspose.svg.dom/text/)、[`CDATASection`](../../../aspose.svg.dom/cdatasection/)、[`Comment`](../../../aspose.svg.dom/comment/)、[`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction/) 、 またはXPathNamespaceノード。コンテキスト ノードが[`Text`](../../../aspose.svg.dom/text/)または[`CDATASection`](../../../aspose.svg.dom/cdatasection/) の場合、ノードが空の でない限り、コンテキストは XPath から見た論理テキスト ノード全体として解釈されます。 |
| type | XPathResultType | 特定の場合`タイプ`が指定されている場合、結果は XPath 変換に依存する 指定された型を返すように強制され、目的の強制が不可能な場合は失敗します。これは の値の1つである必要があります[`XPathResultType`](../../xpathresulttype/). |
| result | Object | の`結果`このメソッドによって を再利用して返すことができる特定の結果オブジェクトを指定します。これが次のように指定されている場合`ヌル`または実装が指定された 結果を再利用しない場合、新しい結果オブジェクトが構築されて返されます。 XPath 1.0 の結果の場合、このオブジェクトはタイプの になります。[`IXPathResult`](../../ixpathresult/). |

### 戻り値

XPath 式の評価の結果。 XPath 1.0 の結果の場合、このオブジェクトはタイプの になります。[`IXPathResult`](../../ixpathresult/).

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: 指定された型を返すように結果を変換できない場合に発生します。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | WRONG_DOCUMENT_ERR: ノードは、 によってサポートされていないドキュメントからのものです。[`IXPathEvaluator`](../../ixpathevaluator/)これを作成した[`IXPathExpression`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: ノードが XPath コンテキスト ノード として許可されているタイプではないか、リクエスト タイプがこれによって許可されていません[`IXPathExpression`](../). |

### 関連項目

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.svg.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* 名前空間 [Aspose.Svg.Dom.XPath](../../ixpathexpression/)
* 組み立て [Aspose.SVG](../../../)


