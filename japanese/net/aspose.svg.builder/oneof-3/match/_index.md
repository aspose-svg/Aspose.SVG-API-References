---
title: "OneOf-3.Match"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "OneOf Match メソッドです。提供された関数のうち、値の基になる型に基づいて1つを実行します。"
type: docs
weight: 20
url: /ja/net/aspose.svg.builder/oneof-3/match/
---
## OneOf<T1,T2,T3>.Match<TResult> method

値の基になる型に基づいて、提供された関数のうちの一つを実行します。

```csharp
public TResult Match<TResult>(Func<T1, TResult> func1, Func<T2, TResult> func2, 
    Func<T3, TResult> func3)
```

| パラメータ | 説明 |
| --- | --- |
| TResult | 関数の戻り値の型です。 |
| func1 | 値が T1 型の場合に実行する関数です。 |
| func2 | 値が T2 型の場合に実行する関数です。 |
| func3 | 値が T3 型の場合に実行する関数です。 |

### 戻り値

実行された関数の結果です。

### 参照

* class [OneOf&lt;T1,T2,T3&gt;](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
