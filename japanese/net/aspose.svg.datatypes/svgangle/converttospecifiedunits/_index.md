---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGAngle ConvertToSpecifiedUnits メソッド。 同じ基礎となる格納値を保持しますが、格納された単位識別子を指定された unitType にリセットします。 オブジェクト属性 unitType、valueInSpecifiedUnits、valueAsString はこのメソッドの結果として変更される可能性があります。"
type: docs
weight: 50
url: /ja/net/aspose.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

同じ基礎となる格納値を保持しつつ、格納された単位識別子を指定された unitType にリセットします。このメソッドの結果として、オブジェクト属性の unitType、valueInSpecifiedUnits、valueAsString が変更される可能性があります。

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| unitType | UInt16 | 切り替える単位タイプ (例: SVG_ANGLETYPE_DEG)。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) が、unitType が SVG_ANGLETYPE_UNKNOWN であるか、有効な単位タイプ定数でない場合に発生します（このインターフェイスで定義されている他の SVG_ANGLETYPE_* 定数のいずれか）。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) 角度が読み取り専用属性に対応している場合、またはオブジェクト自体が読み取り専用の場合に発生します。 |

### 参照

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
