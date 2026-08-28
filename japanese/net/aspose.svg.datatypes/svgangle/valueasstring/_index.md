---
title: "SVGAngle.ValueAsString"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGAngle ValueAsString プロパティ。unitType で表される単位での角度値を文字列として保持します。この属性を設定すると、value、valueInSpecifiedUnits、および unitType が自動的に更新され、この設定を反映します。"
type: docs
weight: 30
url: /ja/net/aspose.svg.datatypes/svgangle/valueasstring/
---
## SVGAngle.ValueAsString property

角度の値は unitType で表される単位の文字列値です。この属性を設定すると、value、valueInSpecifiedUnits、unitType が自動的に更新され、この設定を反映します。

```csharp
public string ValueAsString { get; set; }
```

### Property Value

文字列としての値です。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`SYNTAX_ERR`](../../../aspose.svg.dom/domexception/syntax_err/) は、割り当てられた文字列が有効な角度として解析できない場合に発生します。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) 角度が読み取り専用属性に対応している場合、またはオブジェクト自体が読み取り専用の場合に発生します。 |

### 参照

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
