---
title: "Document.GetElementsByTagName"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Document GetElementsByTagName メソッド。 このメソッドは、指定されたタグ名を持つ要素の HTMLCollection を返します。"
type: docs
weight: 980
url: /ja/net/aspose.svg.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

このメソッドは、指定されたタグ名を持つ要素の [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) を返します。

ルートノードを含む完全なドキュメントが検索されます。返される [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) はライブであり、再度このメソッドを呼び出さなくても DOM ツリーと自動的に同期するように自動で更新されます。

```csharp
public HTMLCollection GetElementsByTagName(string tagname)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| tagname | String | 要素の名前を表す文字列です。特別な文字列 "*" はすべての要素を表します。 |

### 戻り値

ツリー内に出現する順序で見つかった要素のライブ [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) です。

## 備考

公式の [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname) を参照してください。

### 参照

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
