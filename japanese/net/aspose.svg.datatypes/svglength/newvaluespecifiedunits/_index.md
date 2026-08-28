---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGLength NewValueSpecifiedUnits メソッド。 値を関連付けられた unitType を持つ数値としてリセットし、オブジェクト上のすべての属性の値を置き換えます。"
type: docs
weight: 60
url: /ja/net/aspose.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

関連付けられた unitType を持つ数値として値をリセットし、オブジェクト上のすべての属性の値を置き換えます。

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| unitType | UInt16 | 値のユニットタイプ。 |
| valueInSpecifiedUnits | Single | 新しい値.. |

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | コード [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) は、unitType が SVG_LENGTHTYPE_UNKNOWN であるか、有効なユニットタイプ定数（このインターフェイスで定義された他の SVG_LENGTHTYPE_* 定数のいずれか）でない場合に発生します。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | コード [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) は、長さが読み取り専用属性に対応している場合、またはオブジェクト自体が読み取り専用の場合に発生します。 |

### 参照

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
