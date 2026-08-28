---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGAngle NewValueSpecifiedUnits メソッド。関連付けられた unitType を持つ数値として値をリセットし、オブジェクト上のすべての属性の値を置き換えます。"
type: docs
weight: 60
url: /ja/net/aspose.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

関連付けられた unitType を持つ数値として値をリセットし、オブジェクト上のすべての属性の値を置き換えます。

```csharp
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newUnitType | UInt16 | 値の単位タイプ（例: SVG_ANGLETYPE_DEG）。 |
| valueInSpecifiedUnits | Single | 角度の値です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) が、unitType が SVG_ANGLETYPE_UNKNOWN であるか、有効な単位タイプ定数でない場合に発生します（このインターフェイスで定義されている他の SVG_ANGLETYPE_* 定数のいずれか）。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) 角度が読み取り専用属性に対応している場合、またはオブジェクト自体が読み取り専用の場合に発生します。 |

### 参照

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
