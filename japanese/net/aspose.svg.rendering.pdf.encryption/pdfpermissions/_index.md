---
title: "PdfPermissions 列挙体"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Rendering.Pdf.Encryption.PdfPermissions 列挙体。この列挙体は PDF のユーザー権限を表します。"
type: docs
weight: 5000
url: /ja/net/aspose.svg.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

この列挙型は PDF に対するユーザーの権限を表します。

```csharp
[Flags]
public enum PdfPermissions
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| PrintDocument | `4` | (リビジョン 2 のセキュリティハンドラ) 文書を印刷します。(リビジョン 3 以上のセキュリティハンドラ) 文書を印刷します（PrintingQuality が設定されているかどうかに応じて、最高品質でない場合があります）。 |
| ModifyContent | `8` | ModifyTextAnnotations、FillForm、および 11 で制御される操作以外の操作で文書の内容を変更します。 |
| ExtractContent | `10` | (リビジョン 2 のセキュリティハンドラ) 文書からテキストやグラフィックをコピーまたは抽出します（障害を持つユーザーへのアクセシビリティ支援やその他の目的のためにテキストやグラフィックを抽出することを含みます）。(リビジョン 3 以上のセキュリティハンドラ) ExtractContentWithDisabilities で制御される操作以外の操作で文書からテキストやグラフィックをコピーまたは抽出します。 |
| ModifyTextAnnotations | `20` | テキスト注釈を追加または変更し、インタラクティブなフォームフィールドに入力し、さらに ModifyContent が設定されている場合はインタラクティブなフォームフィールド（署名フィールドを含む）を作成または変更します。 |
| FillForm | `100` | (リビジョン 3 以上のセキュリティハンドラ) ModifyTextAnnotations がクリアされていても、既存のインタラクティブなフォームフィールド（署名フィールドを含む）に入力します。 |
| ExtractContentWithDisabilities | `200` | (リビジョン 3 以上のセキュリティハンドラ) テキストやグラフィックを抽出します（障害を持つユーザーへのアクセシビリティ支援やその他の目的のため）。 |
| AssembleDocument | `400` | (リビジョン 3 以上のセキュリティハンドラ) ModifyContent がクリアされていても、文書を組み立てます（ページの挿入、回転、削除やブックマーク・サムネイル画像の作成）。 |
| PrintingQuality | `800` | (リビジョン 3 以上のセキュリティハンドラ) PDF コンテンツの忠実なデジタルコピーを生成できる表現に文書を印刷します。このビットがクリアされ（かつビット 3 が設定されている）場合、印刷は外観の低レベル表現に制限され、品質が低下する可能性があります。 |

### 参照

* namespace [Aspose.Svg.Rendering.Pdf.Encryption](../../aspose.svg.rendering.pdf.encryption/)
* assembly [Aspose.SVG](../../)
