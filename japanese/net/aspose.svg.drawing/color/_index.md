---
title: "Color クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Drawing.Color クラス。Color クラスでは、Red-Green-Blue RGB 値、Hue-Saturation-Luminosity HSL 値、Hue-Saturation-Value HSV 値、Hue-Whiteness-Blackness HWB 値、lightness-A-B LAB 値、Luminance-Chroma-Hue LCH 値、Cyan-Magenta-Yellow-Key CMYK 値、Natural colors NCOL 値、またはカラー名で色を指定できます。透明度を示す Alpha チャネルも利用可能です。"
type: docs
weight: 3390
url: /ja/net/aspose.svg.drawing/color/
---
## Color class

Color クラスを使用すると、赤緑青 (RGB) 値、色相-彩度-輝度 (HSL) 値、色相-彩度-明度 (HSV) 値、色相-白度-黒度 (HWB) 値、光度-A-B (LAB) 値、輝度-クロマ-色相 (LCH) 値、シアン-マゼンタ-イエロー-キー (CMYK) 値、自然色 (NCOL) 値、またはカラー名で色を指定できます。透明度を示すアルファチャンネルも利用可能です。

```csharp
public class Color
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Color](color/#constructor)() | `Color` クラスの新しいインスタンスを初期化します。デフォルトの色は黒です。 |
| [Color](color/#constructor_1)(*byte, byte, byte*) | `Color` クラスの新しいインスタンスを初期化します。すべてのカラーコンポーネントは 0〜255 の範囲でなければなりません。 |
| [Color](color/#constructor_5)(*float, float, float*) | `Color` クラスの新しいインスタンスを初期化します。すべてのカラーコンポーネントは 0〜1 の範囲でなければなりません。 |
| [Color](color/#constructor_3)(*int, int, int*) | `Color` クラスの新しいインスタンスを初期化します。すべてのカラーコンポーネントは 0〜255 の範囲でなければなりません。 |
| [Color](color/#constructor_2)(*byte, byte, byte, byte*) | `Color` クラスの新しいインスタンスを初期化します。すべてのカラーコンポーネントは 0〜255 の範囲でなければなりません。 |
| [Color](color/#constructor_6)(*float, float, float, float*) | `Color` クラスの新しいインスタンスを初期化します。すべてのカラーコンポーネントは 0〜1 の範囲でなければなりません。 |
| [Color](color/#constructor_4)(*int, int, int, int*) | `Color` クラスの新しいインスタンスを初期化します。すべてのカラーコンポーネントは 0〜255 の範囲でなければなりません。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Alpha](../../aspose.svg.drawing/color/alpha/) { get; } | カラーのアルファ成分を表します。 |
| [Blue](../../aspose.svg.drawing/color/blue/) { get; } | カラーの青成分を表します。 |
| [Green](../../aspose.svg.drawing/color/green/) { get; } | カラーの緑成分を表します。 |
| [Red](../../aspose.svg.drawing/color/red/) { get; } | カラーの赤成分を表します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromCmyk](../../aspose.svg.drawing/color/fromcmyk/)(*float, float, float, float*) | 要求されたシアン、マゼンタ、イエロー、キー（黒）値を持つ新しい Color を返します。 |
| static [FromCmyka](../../aspose.svg.drawing/color/fromcmyka/)(*float, float, float, float, float*) | 要求されたシアン、マゼンタ、イエロー、キー（黒）およびアルファ値を持つ新しい Color を返します。 |
| static [FromGray](../../aspose.svg.drawing/color/fromgray/)(*float*) | 要求されたグレー値を持つ新しい Color を返します。 |
| static [FromHsl](../../aspose.svg.drawing/color/fromhsl/)(*float, float, float*) | 要求された色相、彩度、彩度値を持つ新しい Color を返します。 |
| static [FromHsla](../../aspose.svg.drawing/color/fromhsla/)(*float, float, float, float*) | 要求された hue、saturation、saturation、alpha の値を持つ新しい Color を返します。 |
| static [FromHsv](../../aspose.svg.drawing/color/fromhsv/)(*float, float, float*) | 要求された hue、saturation、value の値を持つ新しい Color を返します。 |
| static [FromHsva](../../aspose.svg.drawing/color/fromhsva/)(*float, float, float, float*) | 要求された hue、saturation、value、alpha の値を持つ新しい Color を返します。 |
| static [FromHwb](../../aspose.svg.drawing/color/fromhwb/)(*float, float, float*) | 要求された hue、whiteness、blackness の値を持つ新しい Color を返します。 |
| static [FromHwba](../../aspose.svg.drawing/color/fromhwba/)(*float, float, float, float*) | 要求された hue、whiteness、blackness の値を持つ新しい Color を返します。 |
| static [FromInt](../../aspose.svg.drawing/color/fromint/)(*int*) | 要求された ARGB の値を持つ新しい Color を返します。 |
| static [FromLab](../../aspose.svg.drawing/color/fromlab/)(*float, float, float*) | 要求された lightness、A、B の値を持つ新しい Color を返します。 |
| static [FromLaba](../../aspose.svg.drawing/color/fromlaba/)(*float, float, float, float*) | 要求された lightness、A、B、alpha の値を持つ新しい Color を返します。 |
| static [FromLch](../../aspose.svg.drawing/color/fromlch/)(*float, float, float*) | 要求された luminance、chroma、hue の値を持つ新しい Color を返します。 |
| static [FromLcha](../../aspose.svg.drawing/color/fromlcha/)(*float, float, float, float*) | 要求された luminance、chroma、hue、alpha の値を持つ新しい Color を返します。 |
| static [FromOklab](../../aspose.svg.drawing/color/fromoklab/)(*float, float, float*) | OKLAB モデル用の要求された lightness、A、B の値を持つ新しい Color を返します。 |
| static [FromOklaba](../../aspose.svg.drawing/color/fromoklaba/)(*float, float, float, float*) | OKLAB モデル用の要求された lightness、A、B、alpha の値を持つ新しい Color を返します。 |
| static [FromOklch](../../aspose.svg.drawing/color/fromoklch/)(*float, float, float*) | OKLAB モデル用の要求された luminance、chroma、hue の値を持つ新しい Color を返します。 |
| static [FromOklcha](../../aspose.svg.drawing/color/fromoklcha/)(*float, float, float, float*) | OKLAB モデル用の要求された luminance、chroma、hue、alpha の値を持つ新しい Color を返します。 |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb)(*byte, byte, byte*) | 要求された ged、緑、青の値を持つ新しい Color を返します。すべての色成分は 0〜255 の範囲である必要があります。 |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb_2)(*float, float, float*) | 要求された ged、緑、青の値を持つ新しい Color を返します。すべての色成分は 0〜1 の範囲である必要があります。 |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb_1)(*int, int, int*) | 要求された ged、緑、青の値を持つ新しい Color を返します。すべての色成分は 0〜255 の範囲である必要があります。 |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba)(*byte, byte, byte, byte*) | 要求された ged、緑、青、アルファの値を持つ新しい Color を返します。すべての色成分は 0〜255 の範囲である必要があります。 |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba_2)(*float, float, float, float*) | 要求された ged、緑、青、アルファの値を持つ新しい Color を返します。すべての色成分は 0〜1 の範囲である必要があります。 |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba_1)(*int, int, int, int*) | 要求された ged、緑、青、アルファの値を持つ新しい Color を返します。すべての色成分は 0〜255 の範囲である必要があります。 |
| static [FromString](../../aspose.svg.drawing/color/fromstring/)(*string*) | CSS カラーを含む文字列を解析し、新しい Color を返します。 |
| static [FromUint](../../aspose.svg.drawing/color/fromuint/)(*uint*) | 要求された ARGB の値を持つ新しい Color を返します。 |
| [AddLuminosity](../../aspose.svg.drawing/color/addluminosity/)(*float*) | Color のコピーを作成し、輝度とデルタ値の合計を持たせます。 |
| [Convert](../../aspose.svg.drawing/color/convert/)(*[ColorModel](../colormodel/)*) | 指定されたカラーモデルの形式で色成分を返します。 |
| override [Equals](../../aspose.svg.drawing/color/equals/)(*object*) | 指定された `Color` がこのインスタンスと等しいかどうかを判定します。 |
| [GetComplementary](../../aspose.svg.drawing/color/getcomplementary/)() | 元の色のカラーホイール上で反対側に位置する新しい色を返します。 |
| override [GetHashCode](../../aspose.svg.drawing/color/gethashcode/)() | ハッシュコードを返します。 |
| [GetHue](../../aspose.svg.drawing/color/gethue/)() | Color の色相 (Hue) を返します。 |
| [GetLuminosity](../../aspose.svg.drawing/color/getluminosity/)() | Color の輝度を返します。 |
| [GetSaturation](../../aspose.svg.drawing/color/getsaturation/)() | Color の彩度を返します。 |
| [ToInt](../../aspose.svg.drawing/color/toint/)() | Color の ARGB 成分を int にエンコードします。 |
| [ToName](../../aspose.svg.drawing/color/toname/)() | CSS の名前付きカラーリストに一致する場合はその色名を、そうでなければ空文字列を返します。 |
| [ToNaturalColorString](../../aspose.svg.drawing/color/tonaturalcolorstring/)(*int*) | 色文字と数値で距離（パーセンテージ）を指定して、自然色 (NCol) の指定色を返します。 |
| [ToRgbaHexString](../../aspose.svg.drawing/color/torgbahexstring/)() | 16 進数カラーが #RRGGBBAA で指定されたものを返します。 |
| [ToRgbaString](../../aspose.svg.drawing/color/torgbastring/)() | rgba(R, G, B, A) で指定された RGBA カラーを含む文字列を返します。 |
| [ToRgbHexString](../../aspose.svg.drawing/color/torgbhexstring/)() | 16 進数カラーが #RRGGBB で指定されたものを返します。 |
| [ToRgbString](../../aspose.svg.drawing/color/torgbstring/)() | rgb(R, G, B) で指定された RGB カラーを含む文字列を返します。 |
| override [ToString](../../aspose.svg.drawing/color/tostring/)() | RGBA 成分値からなる文字列を返します。 |
| [ToUint](../../aspose.svg.drawing/color/touint/)() | Color の ARGB 成分を unsigned int にエンコードします。 |
| [WithAlpha](../../aspose.svg.drawing/color/withalpha/)(*float*) | 指定されたアルファ成分を持つ Color のコピーを作成します。 |
| [WithHue](../../aspose.svg.drawing/color/withhue/)(*float*) | 指定された色相 (Hue) を持つ Color のコピーを作成します。 |
| [WithLuminosity](../../aspose.svg.drawing/color/withluminosity/)(*float*) | 指定された輝度を持つ Color のコピーを作成します。 |
| [WithSaturation](../../aspose.svg.drawing/color/withsaturation/)(*float*) | 指定された彩度で Color のコピーを作成します。 |

### 参照

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
