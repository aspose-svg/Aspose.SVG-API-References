---
title: "PdfRenderingOptions クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Rendering.Pdf.PdfRenderingOptions クラス。PdfDevice のレンダリングオプションを表します。"
type: docs
weight: 5050
url: /ja/net/aspose.svg.rendering.pdf/pdfrenderingoptions/
---
## PdfRenderingOptions class

[`PdfDevice`](../pdfdevice/) のレンダリングオプションを表します。

```csharp
public class PdfRenderingOptions : RenderingOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfRenderingOptions](pdfrenderingoptions/)() | `PdfRenderingOptions` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundColor](../../aspose.svg.rendering/renderingoptions/backgroundcolor/) { get; set; } | ページごとの背景を塗りつぶす Color を取得または設定します。デフォルト値は Transparent です。 |
| [Css](../../aspose.svg.rendering/renderingoptions/css/) { get; } | [`CssOptions`](../../aspose.svg.rendering/cssoptions/) オブジェクトを取得します。このオブジェクトは css プロパティの処理設定に使用されます。 |
| [DocumentInfo](../../aspose.svg.rendering.pdf/pdfrenderingoptions/documentinfo/) { get; } | 出力 PDF ドキュメントに関する情報を含みます。 |
| [Encryption](../../aspose.svg.rendering.pdf/pdfrenderingoptions/encryption/) { get; set; } | 暗号化の詳細を取得または設定します。設定されていない場合、暗号化は行われません。 |
| [FormFieldBehaviour](../../aspose.svg.rendering.pdf/pdfrenderingoptions/formfieldbehaviour/) { get; set; } | 出力 PDF ドキュメントのフォームフィールドの動作を指定します。 |
| virtual [HorizontalResolution](../../aspose.svg.rendering/renderingoptions/horizontalresolution/) { get; set; } | 内部画像（フィルタ処理中に使用される）の水平解像度をピクセル/インチで設定または取得します。デフォルトではこのプロパティは 300 dpi です。 |
| [IsTaggedPdf](../../aspose.svg.rendering.pdf/pdfrenderingoptions/istaggedpdf/) { get; set; } | `true` の場合、タグ構造を作成します。 |
| [JpegQuality](../../aspose.svg.rendering.pdf/pdfrenderingoptions/jpegquality/) { get; set; } | 画像の JPEG 圧縮品質を指定します（JPEG 圧縮が使用される場合）。デフォルトは 95 です。 |
| [PageSetup](../../aspose.svg.rendering/renderingoptions/pagesetup/) { get; } | ページ設定オブジェクトを取得します。これは出力ページセットの構成に使用されます。 |
| virtual [VerticalResolution](../../aspose.svg.rendering/renderingoptions/verticalresolution/) { get; set; } | 内部画像（フィルタ処理中に使用される）の垂直解像度をピクセル/インチで設定または取得します。デフォルトではこのプロパティは 300 dpi です。 |

### 参照

* class [RenderingOptions](../../aspose.svg.rendering/renderingoptions/)
* namespace [Aspose.Svg.Rendering.Pdf](../../aspose.svg.rendering.pdf/)
* assembly [Aspose.SVG](../../)
