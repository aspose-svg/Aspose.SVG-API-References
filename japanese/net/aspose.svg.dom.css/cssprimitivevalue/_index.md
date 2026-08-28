---
title: "CSSPrimitiveValue クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Css.CSSPrimitiveValue クラス。CSSPrimitiveValue インターフェイスは単一の CSS 値を表します。このインターフェイスは、ブロック内で現在設定されている特定のスタイルプロパティの値を取得したり、ブロック内で特定のスタイルプロパティを明示的に設定したりするために使用できます。このインターフェイスのインスタンスは、CSSStyleDeclaration インターフェイスの getPropertyCSSValue メソッドから取得できる場合があります。CSSPrimitiveValue オブジェクトは CSS プロパティのコンテキスト内でのみ現れます。"
type: docs
weight: 2480
url: /ja/net/aspose.svg.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

CSSPrimitiveValue インターフェイスは単一の CSS 値を表します。このインターフェイスは、ブロック内で現在設定されている特定のスタイルプロパティの値を取得したり、ブロック内で特定のスタイルプロパティを明示的に設定したりするために使用できます。このインターフェイスのインスタンスは、CSSStyleDeclaration インターフェイスの getPropertyCSSValue メソッドから取得できる場合があります。CSSPrimitiveValue オブジェクトは CSS プロパティのコンテキスト内でのみ発生します。

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext/) { get; set; } | [`CSSValue`](../cssvalue/) インターフェイスの CSSText プロパティは、現在の計算済み CSS プロパティ値を表します。 |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | 値のタイプを定義するコードです。 |
| [PrimitiveType](../../aspose.svg.dom.css/cssprimitivevalue/primitivetype/) { get; } | 上記で指定された定数により定義された値のタイプです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | 指定されたオブジェクトがこのインスタンスと等しいかどうかを判断します。 |
| abstract [GetCounterValue](../../aspose.svg.dom.css/cssprimitivevalue/getcountervalue/)() | このメソッドは Counter 値を取得するために使用されます。この CSS 値にカウンタ値が含まれていない場合、DOMException がスローされます。対応するスタイルプロパティの変更は Counter インターフェイスを使用して行うことができます。 |
| abstract [GetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/getfloatvalue/)(*ushort*) | このメソッドは指定された単位で浮動小数点値を取得するために使用されます。この CSS 値に浮動小数点値が含まれていない、または指定された単位に変換できない場合、DOMException がスローされます。 |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | このインスタンスのハッシュコードを返します。 |
| abstract [GetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/getintvalue/)(*ushort*) | このメソッドは指定された単位で整数値を取得するために使用されます。この CSS 値に整数値が含まれていない、または指定された単位に変換できない場合、DOMException がスローされます。 |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| abstract [GetRectValue](../../aspose.svg.dom.css/cssprimitivevalue/getrectvalue/)() | このメソッドは Rect 値を取得するために使用されます。この CSS 値に Rect 値が含まれていない場合、DOMException がスローされます。対応するスタイルプロパティの変更は Rect インターフェイスを使用して行うことができます。 |
| abstract [GetRGBColorValue](../../aspose.svg.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | このメソッドは RGB カラーを取得するために使用されます。この CSS 値に RGB カラー値が含まれていない場合、DOMException がスローされます。対応するスタイルプロパティの変更は RGBColor インターフェイスを使用して行うことができます。 |
| abstract [GetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/getstringvalue/)() | このメソッドは文字列値を取得するために使用されます。CSS 値に文字列値が含まれていない場合、DOMException がスローされます。 |
| abstract [SetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/setfloatvalue/)(*ushort, float*) | 指定された単位で浮動小数点値を設定するメソッドです。この値が付随するプロパティが指定された単位または浮動小数点値を受け付けない場合、値は変更されず、DOMException がスローされます。 |
| abstract [SetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/setintvalue/)(*ushort, int*) | 指定された単位で整数値を設定するメソッドです。この値が付随するプロパティが指定された単位または整数値を受け付けない場合、値は変更されず、DOMException がスローされます。 |
| abstract [SetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/setstringvalue/)(*ushort, string*) | 指定された単位で文字列値を設定するメソッドです。この値が付随するプロパティが指定された単位または文字列値を受け付けない場合、値は変更されず、DOMException がスローされます。 |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | このインスタンスを表す String を返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [CSS_ATTR](../../aspose.svg.dom.css/cssprimitivevalue/css_attr/) | この値は属性関数です。値は getStringValue メソッドを使用して取得できます。 |
| const [CSS_CH](../../aspose.svg.dom.css/cssprimitivevalue/css_ch/) | この値は長さ（ch）です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_CM](../../aspose.svg.dom.css/cssprimitivevalue/css_cm/) | この値は長さ（cm）です。値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_COUNTER](../../aspose.svg.dom.css/cssprimitivevalue/css_counter/) | この値はカウンタまたはカウンタ関数です。 この値は GetCounterValue メソッドを使用して取得できます。 |
| const [CSS_DEG](../../aspose.svg.dom.css/cssprimitivevalue/css_deg/) | この値は角度（deg）です。 この値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_DIMENSION](../../aspose.svg.dom.css/cssprimitivevalue/css_dimension/) | この値は未知の次元を持つ数値です。 この値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_DPCM](../../aspose.svg.dom.css/cssprimitivevalue/css_dpcm/) | この値はセンチメートルあたりドット（dpcm）です。 |
| const [CSS_DPI](../../aspose.svg.dom.css/cssprimitivevalue/css_dpi/) | この値はインチあたりドット（dpi）です。 |
| const [CSS_DPPX](../../aspose.svg.dom.css/cssprimitivevalue/css_dppx/) | この値は ‘px’ 単位あたりドット（dppx）です。 |
| const [CSS_EMS](../../aspose.svg.dom.css/cssprimitivevalue/css_ems/) | この値は長さ（ems）です。 この値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_EXS](../../aspose.svg.dom.css/cssprimitivevalue/css_exs/) | この値は長さ（exs）です。 この値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_FR](../../aspose.svg.dom.css/cssprimitivevalue/css_fr/) | 柔軟な長さまたは flex は fr 単位を持つ次元で、グリッドコンテナの余剰スペースの一部を表します。 |
| const [CSS_GRAD](../../aspose.svg.dom.css/cssprimitivevalue/css_grad/) | この値は角度（grad）です。 この値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_HZ](../../aspose.svg.dom.css/cssprimitivevalue/css_hz/) | この値は周波数（Hz）です。 この値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_IDENT](../../aspose.svg.dom.css/cssprimitivevalue/css_ident/) | この値は識別子です。 この値は getStringValue メソッドを使用して取得できます。 |
| const [CSS_IN](../../aspose.svg.dom.css/cssprimitivevalue/css_in/) | この値は長さ（in）です。 この値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_KHZ](../../aspose.svg.dom.css/cssprimitivevalue/css_khz/) | この値は周波数（kHz）です。 この値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_MM](../../aspose.svg.dom.css/cssprimitivevalue/css_mm/) | この値は長さ（mm）です。 この値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_MS](../../aspose.svg.dom.css/cssprimitivevalue/css_ms/) | この値は時間（ms）です。 この値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_NUMBER](../../aspose.svg.dom.css/cssprimitivevalue/css_number/) | この値は単純な数値です。 この値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_PC](../../aspose.svg.dom.css/cssprimitivevalue/css_pc/) | この値は長さ（pc）です。 この値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_PERCENTAGE](../../aspose.svg.dom.css/cssprimitivevalue/css_percentage/) | この値はパーセンテージです。 この値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_PT](../../aspose.svg.dom.css/cssprimitivevalue/css_pt/) | この値は長さ（pt）です。 この値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_PX](../../aspose.svg.dom.css/cssprimitivevalue/css_px/) | この値は長さ（px）です。 この値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_RAD](../../aspose.svg.dom.css/cssprimitivevalue/css_rad/) | この値は角度（rad）です。 この値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_RECT](../../aspose.svg.dom.css/cssprimitivevalue/css_rect/) | この値は rect 関数です。 この値は GetRectValue メソッドを使用して取得できます。 |
| const [CSS_REM](../../aspose.svg.dom.css/cssprimitivevalue/css_rem/) | この値は長さ（rem）です。 この値は getFloatValue メソッドを使用して取得できます。 |
| const [CSS_RGBCOLOR](../../aspose.svg.dom.css/cssprimitivevalue/css_rgbcolor/) | この値は RGB カラーです。 この値は GetRGBColorValue メソッドを使用して取得できます。 |
| const [CSS_S](../../aspose.svg.dom.css/cssprimitivevalue/css_s/) | この値は時間（秒）です。getFloatValue メソッドを使用して取得できます。 |
| const [CSS_STRING](../../aspose.svg.dom.css/cssprimitivevalue/css_string/) | この値は文字列です。getStringValue メソッドを使用して取得できます。 |
| const [CSS_UNKNOWN](../../aspose.svg.dom.css/cssprimitivevalue/css_unknown/) | この値は認識された CSS2 の値ではありません。cssText 属性を使用してのみ取得できます。 |
| const [CSS_URI](../../aspose.svg.dom.css/cssprimitivevalue/css_uri/) | この値は URI です。getStringValue メソッドを使用して取得できます。 |
| const [CSS_VH](../../aspose.svg.dom.css/cssprimitivevalue/css_vh/) | この値はビューポート全体の高さのパーセンテージです。 |
| const [CSS_VMAX](../../aspose.svg.dom.css/cssprimitivevalue/css_vmax/) | この値はビューポートの幅または高さのパーセンテージで、より大きい方です。 |
| const [CSS_VMIN](../../aspose.svg.dom.css/cssprimitivevalue/css_vmin/) | この値はビューポートの幅または高さのパーセンテージで、より小さい方です。 |
| const [CSS_VW](../../aspose.svg.dom.css/cssprimitivevalue/css_vw/) | この値はビューポート全体の幅のパーセンテージです。 |
| const [CSS_X](../../aspose.svg.dom.css/cssprimitivevalue/css_x/) | この値は ‘px’ 単位あたりのドット数（x）です。 |

### 参照

* class [CSSValue](../cssvalue/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
