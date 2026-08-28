---
title: "SVGLength クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.DataTypes.SVGLength クラス。SVGLength インターフェイスは長さの基本データ型に対応します。SVGLength オブジェクトは読み取り専用に指定でき、これはオブジェクトの変更を試みると、以下に記載の例外がスローされることを意味します"
type: docs
weight: 2210
url: /ja/net/aspose.svg.datatypes/svglength/
---
## SVGLength class

SVGLength インターフェイスは length 基本データ型に対応します。SVGLength オブジェクトは読み取り専用に指定でき、オブジェクトの変更を試みると例外がスローされます（以下参照）。

```csharp
public class SVGLength : SVGValueType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [UnitType](../../aspose.svg.datatypes/svglength/unittype/) { get; } | このインターフェイスで定義されている SVG_LENGTHTYPE_* 定数のいずれかによって指定される値の型です。 |
| [Value](../../aspose.svg.datatypes/svglength/value/) { get; set; } | ユーザー単位での浮動小数点値としての値です。この属性を設定すると、valueInSpecifiedUnits と valueAsString が自動的に更新され、この設定を反映します。 |
| [ValueAsString](../../aspose.svg.datatypes/svglength/valueasstring/) { get; set; } | unitType で表される単位での文字列値としての値です。この属性を設定すると、value、valueInSpecifiedUnits、unitType が自動的に更新され、この設定を反映します。 |
| [ValueInSpecifiedUnits](../../aspose.svg.datatypes/svglength/valueinspecifiedunits/) { get; set; } | unitType で表される単位での浮動小数点値としての値です。この属性を設定すると、value と valueAsString が自動的に更新され、この設定を反映します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.svg.datatypes/svglength/converttospecifiedunits/)(*ushort*) | 同じ基礎となる格納値を保持しつつ、格納された単位識別子を指定された unitType にリセットします。このメソッドの結果として、オブジェクト属性 unitType、valueInSpecifiedUnits、valueAsString が変更される可能性があります。例えば、元の値が "0.5cm" で、このメソッドがミリメートルに変換するために呼び出された場合、unitType は SVG_LENGTHTYPE_MM に変更され、valueInSpecifiedUnits は数値の 5 に変更され、valueAsString は "5mm" に変更されます。 |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | アンマネージドリソースと、オプションでマネージドリソースを解放します。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [NewValueSpecifiedUnits](../../aspose.svg.datatypes/svglength/newvaluespecifiedunits/)(*ushort, float*) | 関連付けられた unitType を持つ数値として値をリセットし、オブジェクト上のすべての属性の値を置き換えます。 |
| override [ToString](../../aspose.svg.datatypes/svglength/tostring/)() | このインスタンスを表す String を返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.svg.datatypes/svglength/svg_lengthtype_cm/) | CSS2 で定義された cm 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_EMS](../../aspose.svg.datatypes/svglength/svg_lengthtype_ems/) | CSS2 で定義された em 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_EXS](../../aspose.svg.datatypes/svglength/svg_lengthtype_exs/) | CSS2 で定義された ex 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_IN](../../aspose.svg.datatypes/svglength/svg_lengthtype_in/) | CSS2 で定義された in 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_MM](../../aspose.svg.datatypes/svglength/svg_lengthtype_mm/) | CSS2 で定義された mm 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.svg.datatypes/svglength/svg_lengthtype_number/) | 単位タイプが提供されていません（つまり、単位なしの値が指定されました）。これはユーザー単位の値を示します。 |
| const [SVG_LENGTHTYPE_PC](../../aspose.svg.datatypes/svglength/svg_lengthtype_pc/) | CSS2 で定義された pc 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.svg.datatypes/svglength/svg_lengthtype_percentage/) | パーセンテージ値が指定されました。 |
| const [SVG_LENGTHTYPE_PT](../../aspose.svg.datatypes/svglength/svg_lengthtype_pt/) | CSS2 で定義された pt 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_PX](../../aspose.svg.datatypes/svglength/svg_lengthtype_px/) | CSS2 で定義された px 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.svg.datatypes/svglength/svg_lengthtype_unknown/) | 単位タイプは事前定義された単位タイプのいずれでもありません。このタイプの新しい値を定義しようとしたり、既存の値をこのタイプに切り替えようとすることは無効です。 |

### 参照

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
