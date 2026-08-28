---
title: "Document.CreateElement"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Document CreateElement メソッド。localName で指定された HTML 要素を作成します。localName が認識されない場合は HTMLUnknownElement を返します"
type: docs
weight: 850
url: /ja/net/aspose.svg.dom/document/createelement/
---
## Document.CreateElement method

localName で指定された HTML 要素を作成します。localName が認識されない場合は HTMLUnknownElement を作成します。

```csharp
public Element CreateElement(string localName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | String | 作成する要素のタイプを指定する文字列です。作成された要素の nodeName は localName の値で初期化されます。このメソッドでは修飾名（例: "html:a"）を使用しないでください。HTML ドキュメント上で呼び出すと、createElement() は localName を小文字に変換してから要素を作成します。 |

### 戻り値

新しい [`Element`](../../element/)です。

### 参照

* class [Element](../../element/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
