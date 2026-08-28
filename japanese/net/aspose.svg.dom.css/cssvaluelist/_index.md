---
title: "CSSValueList クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Css.CSSValueList クラス。CSSValueList インターフェイスは、CSS 値の順序付けられたコレクションの抽象化を提供します。"
type: docs
weight: 2500
url: /ja/net/aspose.svg.dom.css/cssvaluelist/
---
## CSSValueList class

CSSValueList インターフェイスは、CSS 値の順序付けされたコレクションの抽象化を提供します。

```csharp
public class CSSValueList : CSSValue, ICSSValueList, IEnumerable<CSSValue>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [CSSValueList](cssvaluelist/#constructor)() | `CSSValueList` クラスの新しいインスタンスを初期化します。 |
| [CSSValueList](cssvaluelist/#constructor_1)(*params CSSValue[]*) | `CSSValueList` クラスの新しいインスタンスを初期化します。 |
| [CSSValueList](cssvaluelist/#constructor_2)(*IEnumerable&lt;CSSValue&gt;*) | `CSSValueList` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [CSSText](../../aspose.svg.dom.css/cssvaluelist/csstext/) { get; set; } | [`CSSValue`](../cssvalue/) インターフェイスの CSSText プロパティは、現在の計算済み CSS プロパティ値を表します。 |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | 値のタイプを定義するコードです。 |
| [Item](../../aspose.svg.dom.css/cssvaluelist/item/) { get; } | 指定されたインデックスの [`CSSValue`](../cssvalue/) を取得します。 |
| [Length](../../aspose.svg.dom.css/cssvaluelist/length/) { get; } | CSSValueList インターフェイスの length 読み取り専用プロパティは、リスト内の CSSValue の数を表します。インデックスの有効な値の範囲は 0 から length-1 までです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | 指定されたオブジェクトがこのインスタンスと等しいかどうかを判断します。 |
| [GetEnumerator](../../aspose.svg.dom.css/cssvaluelist/getenumerator/)() | コレクションを反復処理する列挙子を返します。 |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | このインスタンスのハッシュコードを返します。 |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvaluelist/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | このインスタンスを表す String を返します。 |

### 参照

* class [CSSValue](../cssvalue/)
* interface [ICSSValueList](../icssvaluelist/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
