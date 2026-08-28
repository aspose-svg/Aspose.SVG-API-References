---
title: "OneOfT1T2T3 クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.OneOf3T1T2T3 クラス。T1、T2、または T3 の 3 つの異なる型のいずれかになる値を表します。"
type: docs
weight: 940
url: /ja/net/aspose.svg.builder/oneof-3/
---
## OneOf<T1,T2,T3> class

T1、T2、または T3 の 3 つの異なる型のいずれかになる可能性がある値を表します。

```csharp
public class OneOf<T1, T2, T3>
```

| パラメータ | 説明 |
| --- | --- |
| T1 | 最初の可能な値の型です。 |
| T2 | 2番目の可能な値の型です。 |
| T3 | 3 番目の可能な値の型です。 |

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [OneOf](oneof/#constructor)(*T1*) | OneOf クラスの新しいインスタンスを、型 T1 の値で初期化します。 |
| [OneOf](oneof/#constructor_1)(*T2*) | OneOf クラスの新しいインスタンスを、型 T2 の値で初期化します。 |
| [OneOf](oneof/#constructor_2)(*T3*) | T3 型の値で OneOf クラスの新しいインスタンスを初期化します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Match<TResult>](../../aspose.svg.builder/oneof-3/match/)(*Func&lt;T1, TResult&gt;, Func&lt;T2, TResult&gt;, Func&lt;T3, TResult&gt;*) | 値の基になる型に基づいて、提供された関数のうちの一つを実行します。 |
| [implicit operator](../../aspose.svg.builder/oneof-3/op_implicit/#op_implicit) | (3 演算子) |

### 参照

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
