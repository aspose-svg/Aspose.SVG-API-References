---
title: "Document.GetElementById"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Document GetElementById メソッド。このメソッドは、id プロパティが指定された文字列と一致する要素を表す Element オブジェクトを返します。要素の ID は指定された場合に一意である必要があるため、特定の要素に迅速にアクセスする便利な方法です。"
type: docs
weight: 960
url: /ja/net/aspose.svg.dom/document/getelementbyid/
---
## Document.GetElementById method

このメソッドは、id プロパティが指定された文字列と一致する要素を表す [`Element`](../../element/) オブジェクトを返します。要素の ID は指定された場合に一意である必要があるため、特定の要素に迅速にアクセスする便利な方法です。

ID を持たない要素にアクセスする必要がある場合は、[`QuerySelector`](../queryselector/) を使用して任意のセレクタで要素を検索できます。

```csharp
public Element GetElementById(string elementId)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| elementId | String | 取得対象要素の ID。ID は文書内で一意である大文字小文字を区別する文字列で、同一の ID を持つ要素は一つだけです。 |

### 戻り値

指定された ID に一致する DOM 要素を表す [`Element`](../../element/) オブジェクト、または文書内に一致する要素が見つからなかった場合は null。

## 備考

公式の [spec](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid) を参照してください。

### 参照

* class [Element](../../element/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
