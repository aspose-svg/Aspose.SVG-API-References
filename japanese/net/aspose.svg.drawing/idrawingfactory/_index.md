---
title: "IDrawingFactory インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Drawing.IDrawingFactory インターフェイス。描画関連オブジェクトを作成するためのファクトリを表します"
type: docs
weight: 3460
url: /ja/net/aspose.svg.drawing/idrawingfactory/
---
## IDrawingFactory interface

描画関連オブジェクトを作成するファクトリを表します。

```csharp
public interface IDrawingFactory : IDisposable
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CreateInterpolationColor](../../aspose.svg.drawing/idrawingfactory/createinterpolationcolor/)(*Color, float*) | 指定された色と位置で補間色を作成します。 |
| [CreateLinearGradientBrush](../../aspose.svg.drawing/idrawingfactory/createlineargradientbrush/)(*RectangleF, IInterpolationColor[]*) | 指定されたパラメータで線形グラデーションブラシを作成します。 |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix)() | 新しい単位行列を作成します。 |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_1)(*[IMatrix](../imatrix/)*) | 指定された行列と同じ内容の新しい行列を作成します。 |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_2)(*float, float, float, float, float, float*) | 指定された要素で新しい行列を作成します。 |
| [CreateSolidBrush](../../aspose.svg.drawing/idrawingfactory/createsolidbrush/)(*Color*) | 指定された色でソリッドブラシを作成します。 |
| [CreateTextureBrush](../../aspose.svg.drawing/idrawingfactory/createtexturebrush/)(*byte[]*) | 指定されたパラメータでテクスチャブラシを作成します。 |

### 参照

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
