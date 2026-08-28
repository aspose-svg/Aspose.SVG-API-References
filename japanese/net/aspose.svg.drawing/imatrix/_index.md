---
title: "IMatrix インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Drawing.IMatrix インターフェイス。変換に使用される行列を表します"
type: docs
weight: 3500
url: /ja/net/aspose.svg.drawing/imatrix/
---
## IMatrix interface

変換に使用される行列を表します。

```csharp
public interface IMatrix
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsIdentity](../../aspose.svg.drawing/imatrix/isidentity/) { get; } | この行列が単位行列かどうかを示す値を取得します。 |
| [IsInvertible](../../aspose.svg.drawing/imatrix/isinvertible/) { get; } | この行列が逆行列可能かどうかを示す値を取得します。 |
| [M11](../../aspose.svg.drawing/imatrix/m11/) { get; set; } | 行列の第1行第1列の値を取得または設定します。 |
| [M12](../../aspose.svg.drawing/imatrix/m12/) { get; set; } | 行列の第1行第2列の値を取得または設定します。 |
| [M21](../../aspose.svg.drawing/imatrix/m21/) { get; set; } | 行列の第2行第1列の値を取得または設定します。 |
| [M22](../../aspose.svg.drawing/imatrix/m22/) { get; set; } | 行列の第2行第2列の値を取得または設定します。 |
| [M31](../../aspose.svg.drawing/imatrix/m31/) { get; set; } | 行列の第3行第1列の値を取得または設定します。 |
| [M32](../../aspose.svg.drawing/imatrix/m32/) { get; set; } | 行列の第3行第2列の値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../aspose.svg.drawing/imatrix/clone/)() | この行列のコピーを作成します。 |
| [GetElements](../../aspose.svg.drawing/imatrix/getelements/)() | 行列の要素を配列として取得します。 |
| [Invert](../../aspose.svg.drawing/imatrix/invert/)() | この行列を反転します。 |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply)(*IMatrix*) | この行列を別の行列と乗算します。 |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply_1)(*IMatrix, [WebMatrixOrder](../webmatrixorder/)*) | この行列を指定された順序で別の行列と乗算します。 |
| [Reset](../../aspose.svg.drawing/imatrix/reset/)() | 行列を単位行列にリセットします。 |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate)(*float*) | 行列を指定された角度で回転させます。 |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate_1)(*float, [WebMatrixOrder](../webmatrixorder/)*) | 行列を指定された順序で指定された角度だけ回転させます。 |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat)(*float, PointF*) | 行列を指定された点を中心に指定された角度だけ回転させます。 |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat_1)(*float, PointF, [WebMatrixOrder](../webmatrixorder/)*) | 指定された順序で、指定された点の周りを指定された角度だけ行列を回転させます。 |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale)(*float, float*) | 指定されたスケール係数で行列を均等に拡大縮小します。 |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | 指定された順序で、指定されたスケール係数に従って行列を拡大縮小します。 |
| [Skew](../../aspose.svg.drawing/imatrix/skew/)(*float, float*) | 行列にせん断変換を適用します。 |
| [TransformPoint](../../aspose.svg.drawing/imatrix/transformpoint/)(*PointF*) | この行列を使用して指定された点を変換します。 |
| [TransformPoints](../../aspose.svg.drawing/imatrix/transformpoints/)(*PointF[]*) | この行列を使用して点の配列を変換します。 |
| [TransformRectangle](../../aspose.svg.drawing/imatrix/transformrectangle/)(*RectangleF*) | この行列を使用して指定された矩形を変換します。 |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate)(*float, float*) | 指定されたオフセット値で行列を平行移動させます。 |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | 指定された順序で、指定されたオフセット値に従って行列を平行移動させます。 |

### 参照

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
