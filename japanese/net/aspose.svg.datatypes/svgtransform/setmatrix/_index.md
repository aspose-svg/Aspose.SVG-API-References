---
title: "SVGTransform.SetMatrix"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGTransform SetMatrix メソッド。 パラメータ matrix で新しい変換を定義し、変換タイプを SVG_TRANSFORM_MATRIX に設定します。 パラメータ matrix の値はコピーされ、matrix パラメータは SVGTransformmatrix を置き換えません。"
type: docs
weight: 40
url: /ja/net/aspose.svg.datatypes/svgtransform/setmatrix/
---
## SVGTransform.SetMatrix method

変換タイプを SVG_TRANSFORM_MATRIX に設定し、parameter matrix で新しい変換を定義します。parameter matrix の値はコピーされ、matrix パラメータは SVGTransform::matrix を置き換えません。

```csharp
public void SetMatrix(SVGMatrix matrix)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| matrix | SVGMatrix | 変換用の新しい行列。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | コード [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/)。読み取り専用属性の値を変更しようとしたときに発生します。 |

### 参照

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
