---
title: "CSSValue クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Css.CSSValue クラス。シンプルまたは複合的な値を表します。CSSValue オブジェクトは CSS プロパティのコンテキスト内でのみ発生します。"
type: docs
weight: 2490
url: /ja/net/aspose.svg.dom.css/cssvalue/
---
## CSSValue class

単純または複合的な値を表します。CSSValue オブジェクトは CSS プロパティのコンテキスト内でのみ発生します。

```csharp
public abstract class CSSValue : DOMObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext/) { get; set; } | `CSSValue` インターフェイスの CSSText プロパティは、現在の計算済み CSS プロパティ値を表します。 |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | 値のタイプを定義するコードです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | 指定されたオブジェクトがこのインスタンスと等しいかどうかを判断します。 |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | このインスタンスのハッシュコードを返します。 |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | このインスタンスを表す String を返します。 |
| [operator ==](../../aspose.svg.dom.css/cssvalue/op_equality/) | 演算子 == を実装します。 |
| [operator !=](../../aspose.svg.dom.css/cssvalue/op_inequality/) | != 演算子を実装します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [CSS_CUSTOM](../../aspose.svg.dom.css/cssvalue/css_custom/) | この値はカスタム値です。 |
| const [CSS_INHERIT](../../aspose.svg.dom.css/cssvalue/css_inherit/) | この値は継承され、cssText に "inherit" が含まれています。 |
| const [CSS_PRIMITIVE_VALUE](../../aspose.svg.dom.css/cssvalue/css_primitive_value/) | この値はプリミティブ値であり、CSSValue インターフェイスのこのインスタンスに対してバインディング固有のキャストメソッドを使用することで CSSPrimitiveValue インターフェイスのインスタンスを取得できます。 |
| const [CSS_VALUE_LIST](../../aspose.svg.dom.css/cssvalue/css_value_list/) | この値は CSSValue リストであり、CSSValue インターフェイスのこのインスタンスに対してバインディング固有のキャストメソッドを使用することで CSSValueList インターフェイスのインスタンスを取得できます。 |

### 参照

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
