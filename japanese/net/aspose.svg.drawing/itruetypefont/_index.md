---
title: "ITrueTypeFont インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Drawing.ITrueTypeFont インターフェイス。TrueType フォントを操作するためのメソッドを宣言します。"
type: docs
weight: 3540
url: /ja/net/aspose.svg.drawing/itruetypefont/
---
## ITrueTypeFont interface

TrueType フォントを操作するためのメソッドを宣言します。

```csharp
public interface ITrueTypeFont
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DataSize](../../aspose.svg.drawing/itruetypefont/datasize/) { get; } | フォントデータのサイズ（バイト単位）を取得します。 |
| [FamilyName](../../aspose.svg.drawing/itruetypefont/familyname/) { get; } | フォントファミリーの名前を取得します。 |
| [FullFontName](../../aspose.svg.drawing/itruetypefont/fullfontname/) { get; } | 完全なフォント名は通常、Family と Subfamily の名前の組み合わせで表されます。 |
| [Style](../../aspose.svg.drawing/itruetypefont/style/) { get; } | font-face ルールの値とフォントからのデータを組み合わせたフォントスタイルを取得します。 |
| [SubFamilyName](../../aspose.svg.drawing/itruetypefont/subfamilyname/) { get; } | サブファミリー名は、同じファミリー名を持つグループ内でフォントを区別します。これはスタイル（italic、oblique）やウェイト（light、bold、black など）を示すものと想定されます。ウェイトやスタイルに特別な違いがないフォントは、文字列 "Regular" を使用すべきです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetAscent](../../aspose.svg.drawing/itruetypefont/getascent/)(*float*) | 指定されたフォントサイズを使用して、フォントのアセント（ポイント単位）を取得します。 |
| [GetData](../../aspose.svg.drawing/itruetypefont/getdata/)() | フォントデータのストリームを開きます。呼び出し側がストリームの破棄を担当します。 |
| [GetDescent](../../aspose.svg.drawing/itruetypefont/getdescent/)(*float*) | 指定されたフォントサイズを使用して、フォントのディセント（ポイント単位）を取得します。 |

### 参照

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
