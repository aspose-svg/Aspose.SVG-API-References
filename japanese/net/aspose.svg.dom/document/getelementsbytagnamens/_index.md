---
title: "Document.GetElementsByTagNameNS"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Document GetElementsByTagNameNS メソッド。指定されたタグ名で、指定された名前空間に属する要素のリストを返します。ルートノードを含むドキュメント全体が検索されます。"
type: docs
weight: 990
url: /ja/net/aspose.svg.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

指定された名前空間に属し、指定されたタグ名を持つ要素のリストを返します。ルートノードを含む文書全体が検索されます。

```csharp
public HTMLCollection GetElementsByTagNameNS(string namespaceURI, string localName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| namespaceURI | String | 検索対象要素の名前空間 URI。 |
| localName | String | 検索対象要素のローカル名、またはすべての要素にマッチする特別な値 * のいずれかです。 |

### 戻り値

ツリーに現れる順序で取得された要素のライブ [`NodeList`](../../../aspose.svg.collections/nodelist/)。

## 備考

公式の [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens) を参照してください。

### 参照

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
