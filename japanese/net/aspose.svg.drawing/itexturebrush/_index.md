---
title: "ITextureBrush インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Drawing.ITextureBrush インターフェイス。画像を使用してシェイプの内部を塗りつぶすブラシインターフェイスを定義します。"
type: docs
weight: 3520
url: /ja/net/aspose.svg.drawing/itexturebrush/
---
## ITextureBrush interface

画像を使用して形状の内部を塗りつぶすブラシインターフェイスを定義します。

```csharp
public interface ITextureBrush : ITransformableBrush
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ColorMap](../../aspose.svg.drawing/itexturebrush/colormap/) { get; } | 要素数は偶数でなければなりません。偶数インデックスの要素は旧色です。奇数インデックスの要素は新色です。 |
| [Image](../../aspose.svg.drawing/itexturebrush/image/) { get; } | ブラシで使用される画像を取得または設定します。 |
| [ImageArea](../../aspose.svg.drawing/itexturebrush/imagearea/) { get; } | ブラシで使用される画像の領域を指定します。RectangleF.Empty と等しい場合、画像全体が使用されます。座標はピクセル単位です。 |
| [Opacity](../../aspose.svg.drawing/itexturebrush/opacity/) { get; set; } | カラー変換行列の不透明度値を取得します。 |

### 参照

* interface [ITransformableBrush](../itransformablebrush/)
* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
