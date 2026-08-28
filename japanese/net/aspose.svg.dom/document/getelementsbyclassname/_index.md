---
title: "Document.GetElementsByClassName"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Document GetElementsByClassName メソッド。このメソッドは、指定されたすべてのクラス名を持つすべての子要素の配列に似たオブジェクトを返します。"
type: docs
weight: 970
url: /ja/net/aspose.svg.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

このメソッドは、指定されたすべてのクラス名を持つすべての子要素の配列に似たオブジェクトを返します。

ドキュメントオブジェクトで呼び出すと、ルートノードを含むドキュメント全体が検索されます。また、このメソッドは任意の要素でも呼び出すことができ、指定されたルート要素の子孫で、指定されたクラス名を持つ要素のみを返します。

```csharp
public HTMLCollection GetElementsByClassName(string classNames)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| classNames | String | クラス（クラス名）を表す、スペースで区切られた一意のトークンの順序なし集合を含む文字列 |

### 戻り値

見つかった要素のライブ `HTMLCollection`(../../../aspose.svg.collections/htmlcollection/)です。

## 備考

公式の [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname) を参照してください。

### 参照

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
