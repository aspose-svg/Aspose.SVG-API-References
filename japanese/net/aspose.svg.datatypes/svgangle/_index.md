---
title: "SVGAngle クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.DataTypes.SVGAngle クラス。SVGAngle インターフェイスは角度の基本データ型に対応します"
type: docs
weight: 2070
url: /ja/net/aspose.svg.datatypes/svgangle/
---
## SVGAngle class

SVGAngle インターフェイスは、角度の基本データ型に対応します。

```csharp
public class SVGAngle : SVGValueType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [UnitType](../../aspose.svg.datatypes/svgangle/unittype/) { get; } | このインターフェイスで定義された SVG_ANGLETYPE_* 定数のいずれかによって指定された値のタイプです。 |
| [Value](../../aspose.svg.datatypes/svgangle/value/) { get; set; } | 角度の値は度単位の浮動小数点値です。この属性を設定すると、valueInSpecifiedUnits と valueAsString が自動的に更新され、この設定を反映します。 |
| [ValueAsString](../../aspose.svg.datatypes/svgangle/valueasstring/) { get; set; } | 角度の値は unitType で表される単位の文字列値です。この属性を設定すると、value、valueInSpecifiedUnits、unitType が自動的に更新され、この設定を反映します。 |
| [ValueInSpecifiedUnits](../../aspose.svg.datatypes/svgangle/valueinspecifiedunits/) { get; set; } | 角度の値は unitType で表される単位の浮動小数点値です。この属性を設定すると、value と valueAsString が自動的に更新され、この設定を反映します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.svg.datatypes/svgangle/converttospecifiedunits/)(*ushort*) | 同じ基礎となる格納値を保持しつつ、格納された単位識別子を指定された unitType にリセットします。このメソッドの結果として、オブジェクト属性の unitType、valueInSpecifiedUnits、valueAsString が変更される可能性があります。 |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | アンマネージドリソースと、オプションでマネージドリソースを解放します。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [NewValueSpecifiedUnits](../../aspose.svg.datatypes/svgangle/newvaluespecifiedunits/)(*ushort, float*) | 関連付けられた unitType を持つ数値として値をリセットし、オブジェクト上のすべての属性の値を置き換えます。 |
| override [ToString](../../aspose.svg.datatypes/svgangle/tostring/)() | このインスタンスを表す String を返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../aspose.svg.datatypes/svgangle/svg_angletype_deg/) | 単位タイプは明示的に度に設定されました。 |
| const [SVG_ANGLETYPE_GRAD](../../aspose.svg.datatypes/svgangle/svg_angletype_grad/) | 単位タイプはラジアンです。 |
| const [SVG_ANGLETYPE_RAD](../../aspose.svg.datatypes/svgangle/svg_angletype_rad/) | 単位タイプはラジアンです。 |
| const [SVG_ANGLETYPE_UNKNOWN](../../aspose.svg.datatypes/svgangle/svg_angletype_unknown/) | 単位タイプは事前定義された単位タイプのいずれでもありません。このタイプの新しい値を定義しようとしたり、既存の値をこのタイプに切り替えようとすることは無効です。 |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../aspose.svg.datatypes/svgangle/svg_angletype_unspecified/) | 単位タイプが提供されていません（つまり、単位なしの値が指定されました）。角度の場合、単位なしの値は度が指定された場合と同様に扱われます。 |

### 参照

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
