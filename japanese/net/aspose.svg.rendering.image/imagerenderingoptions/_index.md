---
title: "ImageRenderingOptions クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Rendering.Image.ImageRenderingOptions クラス。ImageDevice のレンダリングオプションを表します。このオプションは、出力画像のフォーマット、圧縮、解像度などを指定するために使用されます。"
type: docs
weight: 4940
url: /ja/net/aspose.svg.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

[`ImageDevice`](../imagedevice/) のレンダリングオプションを表します。このオプションは、出力画像のフォーマット、圧縮、解像度などを指定するために使用されます。

```csharp
public class ImageRenderingOptions : RenderingOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | `ImageRenderingOptions` クラスの新しいインスタンスを初期化します；デフォルトの画像形式として Png が使用されます。 |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(*[ImageFormat](../imageformat/)*) | 指定された画像形式で `ImageRenderingOptions` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundColor](../../aspose.svg.rendering/renderingoptions/backgroundcolor/) { get; set; } | ページごとの背景を塗りつぶす Color を取得または設定します。デフォルト値は Transparent です。 |
| [Compression](../../aspose.svg.rendering.image/imagerenderingoptions/compression/) { get; set; } | Tagged Image File Format (TIFF) の [`Compression`](../compression/) を設定または取得します。デフォルトではこのプロパティは LZW です。 |
| [Css](../../aspose.svg.rendering/renderingoptions/css/) { get; } | [`CssOptions`](../../aspose.svg.rendering/cssoptions/) オブジェクトを取得します。このオブジェクトは css プロパティの処理設定に使用されます。 |
| [Format](../../aspose.svg.rendering.image/imagerenderingoptions/format/) { get; set; } | [`ImageFormat`](../imageformat/) を設定または取得します。デフォルトではこのプロパティは Png です。 |
| override [HorizontalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | 出力および内部（フィルタ処理中に使用される）画像の水平解像度を DPI（インチあたりピクセル数）で設定または取得します。デフォルトではこのプロパティは 300 dpi です。 |
| [PageSetup](../../aspose.svg.rendering/renderingoptions/pagesetup/) { get; } | ページ設定オブジェクトを取得します。これは出力ページセットの構成に使用されます。 |
| [Text](../../aspose.svg.rendering.image/imagerenderingoptions/text/) { get; } | テキストレンダリングの構成に使用される [`TextOptions`](../textoptions/) オブジェクトを取得します。 |
| [UseAntialiasing](../../aspose.svg.rendering.image/imagerenderingoptions/useantialiasing/) { get; set; } | アンチエイリアシングを使用するかどうかを指定します。デフォルトではアンチエイリアシングが有効になっています。 |
| override [VerticalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | 出力および内部（フィルタ処理中に使用される）画像の垂直解像度を DPI（インチあたりピクセル数）で設定または取得します。デフォルトではこのプロパティは 300 dpi です。 |

### 参照

* class [RenderingOptions](../../aspose.svg.rendering/renderingoptions/)
* namespace [Aspose.Svg.Rendering.Image](../../aspose.svg.rendering.image/)
* assembly [Aspose.SVG](../../)
