---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGLength ConvertToSpecifiedUnits メソッド。基礎となる格納値はそのまま保持し、格納された単位識別子を指定された unitType にリセットします。このメソッドの結果として、オブジェクト属性の unitType、valueInSpecifiedUnits、valueAsString が変更される可能性があります。例えば、元の値が 0.5cm で、このメソッドをミリメートルに変換するために呼び出した場合、unitType は SVG_LENGTHTYPE_MM に変更され、valueInSpecifiedUnits は数値の 5 に、valueAsString は 5mm に変更されます"
type: docs
weight: 50
url: /ja/net/aspose.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

同じ基礎となる格納値を保持しつつ、格納された単位識別子を指定された unitType にリセットします。このメソッドの結果として、オブジェクト属性 unitType、valueInSpecifiedUnits、valueAsString が変更される可能性があります。例えば、元の値が "0.5cm" で、このメソッドがミリメートルに変換するために呼び出された場合、unitType は SVG_LENGTHTYPE_MM に変更され、valueInSpecifiedUnits は数値の 5 に変更され、valueAsString は "5mm" に変更されます。

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| unitType | UInt16 | 切り替える単位タイプ (例: SVG_LENGTHTYPE_MM)。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | コード [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) は、unitType が SVG_LENGTHTYPE_UNKNOWN であるか、有効なユニットタイプ定数（このインターフェイスで定義された他の SVG_LENGTHTYPE_* 定数のいずれか）でない場合に発生します。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | コード [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) は、長さが読み取り専用属性に対応している場合、またはオブジェクト自体が読み取り専用の場合に発生します。 |

### 参照

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
