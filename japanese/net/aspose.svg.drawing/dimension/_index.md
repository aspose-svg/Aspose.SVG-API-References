---
title: "Dimension クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Drawing.Dimension クラス。次元の基底クラスを提供します。一般的に「次元」とは単位が付いた数値を指し、UnitType によって表されます。"
type: docs
weight: 3410
url: /ja/net/aspose.svg.drawing/dimension/
---
## Dimension class

次元の基底クラスを提供します。一般的な用語 'dimension' は単位が付いた数値を指し、[`UnitType`](../unittype/) によって表されます。

```csharp
public abstract class Dimension : Numeric
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [UnitType](../../aspose.svg.drawing/unit/unittype/) { get; } | 単位のタイプを取得します [`Unit`](../unit/). |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CompareTo](../../aspose.svg.drawing/numeric/compareto/)(*[Numeric](../numeric/)*) | 現在のインスタンスを同じ型の別のオブジェクトと比較し、現在のインスタンスがソート順で前に来るか、後に来るか、または同じ位置にあるかを示す整数を返します。 |
| override [Equals](../../aspose.svg.drawing/unit/equals/)(*object*) | 指定された Object がこのインスタンスと等しいかどうかを判断します。 |
| override [Equals](../../aspose.svg.drawing/numeric/equals/)(*[Unit](../unit/)*) | 指定された [`Unit`](../unit/) がこのインスタンスと等しいかどうかを判断します。 |
| override [GetHashCode](../../aspose.svg.drawing/numeric/gethashcode/)() | このインスタンスのハッシュコードを返します。 |
| [GetValue](../../aspose.svg.drawing/numeric/getvalue/)() | 単位の値を取得します。 |
| [GetValue](../../aspose.svg.drawing/numeric/getvalue/)(*[UnitType](../unittype/)*) | 指定された [`UnitType`](../unittype/) に変換された値を取得します。 |
| override [ToString](../../aspose.svg.drawing/dimension/tostring/)() | このインスタンスを表す String を返します。 |

### 参照

* class [Unit](../unit/)
* class [Numeric](../numeric/)
* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
