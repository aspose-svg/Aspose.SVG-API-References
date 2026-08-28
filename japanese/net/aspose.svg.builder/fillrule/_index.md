---
title: "FillRule 列挙型"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.FillRule 列挙型。SVG グラフィックスにおいて、形状のどの部分が内部か外部かを決定する規則を指定します。"
type: docs
weight: 270
url: /ja/net/aspose.svg.builder/fillrule/
---
## FillRule enumeration

SVG グラフィックスで形状のどの部分が内部か外部かを判断するルールを指定します。

```csharp
public enum FillRule
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Nonzero | `0` | 非ゼロ winding ルール：点が形状の内部にあるかどうかを、点から任意の方向に無限遠までレイを描き、与えられた形状のパスセグメントがレイと交差する回数を数えることで判定します。この回数が奇数の場合、点は内部です；偶数の場合、点は外部です。 |
| Evenodd | `1` | 偶数-奇数 winding ルール：点が形状の内部にあるかどうかを、点から任意の方向に無限遠までレイを描き、与えられた形状のパスセグメントがレイと交差する回数を数えることで判定します。この回数が偶数の場合、点は外部です；奇数の場合、点は内部です。 |

### 参照

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
