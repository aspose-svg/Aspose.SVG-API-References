---
title: "ImageSaveOptions クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Saving.ImageSaveOptions クラス。特定のオプションデータクラスです。"
type: docs
weight: 5690
url: /ja/net/aspose.svg.saving/imagesaveoptions/
---
## ImageSaveOptions class

特定のオプションデータクラスです。

```csharp
public class ImageSaveOptions : ImageRenderingOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | `ImageSaveOptions` クラスの新しいインスタンスを初期化します。デフォルトの画像形式として Png が使用されます。 |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(*[ImageFormat](../../aspose.svg.rendering.image/imageformat/)*) | 初期化に基づく画像形式は [`ImageFormat`](../../aspose.svg.rendering.image/imageformat/) です。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundColor](../../aspose.svg.rendering/renderingoptions/backgroundcolor/) { get; set; } | ページごとの背景を塗りつぶす Color を取得または設定します。デフォルト値は Transparent です。 |
| [Compression](../../aspose.svg.rendering.image/imagerenderingoptions/compression/) { get; set; } | Tagged Image File Format (TIFF) の [`Compression`](../../aspose.svg.rendering.image/compression/) を設定または取得します。デフォルトではこのプロパティは LZW です。 |
| [Css](../../aspose.svg.rendering/renderingoptions/css/) { get; } | [`CssOptions`](../../aspose.svg.rendering/cssoptions/) オブジェクトを取得します。このオブジェクトは css プロパティの処理設定に使用されます。 |
| [Format](../../aspose.svg.rendering.image/imagerenderingoptions/format/) { get; set; } | [`ImageFormat`](../../aspose.svg.rendering.image/imageformat/) を設定または取得します。デフォルトではこのプロパティは Png です。 |
| override [HorizontalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | 出力および内部（フィルタ処理中に使用される）画像の水平解像度を DPI（インチあたりピクセル数）で設定または取得します。デフォルトではこのプロパティは 300 dpi です。 |
| [PageSetup](../../aspose.svg.rendering/renderingoptions/pagesetup/) { get; } | ページ設定オブジェクトを取得します。これは出力ページセットの構成に使用されます。 |
| [Text](../../aspose.svg.rendering.image/imagerenderingoptions/text/) { get; } | [`TextOptions`](../../aspose.svg.rendering.image/textoptions/) オブジェクトを取得します。このオブジェクトはテキストレンダリングの構成に使用されます。 |
| [UseAntialiasing](../../aspose.svg.rendering.image/imagerenderingoptions/useantialiasing/) { get; set; } | アンチエイリアシングを使用するかどうかを指定します。デフォルトではアンチエイリアシングが有効になっています。 |
| override [VerticalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | 出力および内部（フィルタ処理中に使用される）画像の垂直解像度を DPI（インチあたりピクセル数）で設定または取得します。デフォルトではこのプロパティは 300 dpi です。 |

### 参照

* class [ImageRenderingOptions](../../aspose.svg.rendering.image/imagerenderingoptions/)
* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
