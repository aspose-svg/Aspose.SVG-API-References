---
title: "SVGFEColorMatrixElementBuilder.TypeAndValues"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGFEColorMatrixElementBuilder TypeAndValues メソッド。feColorMatrix 要素の type と values 属性を設定し、カラー行列操作とそのパラメータを指定します"
type: docs
weight: 30
url: /ja/net/aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/
---
## SVGFEColorMatrixElementBuilder.TypeAndValues method

feColorMatrix 要素の 'type' と 'values' 属性を設定し、カラー行列の操作とそのパラメータを指定します。

```csharp
public SVGFEColorMatrixElementBuilder TypeAndValues(ColorMatrixOperation type, 
    params double[] values)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | ColorMatrixOperation | カラー行列操作のタイプを表す ColorMatrixOperation 列挙値です |
| values | Double[] | カラー行列操作のパラメータです |

### 戻り値

現在のビルダーインスタンスです。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定されたタイプの要件と提供された値が一致しない場合にスローされます |
| NotSupportedException | サポートされていない行列操作タイプが指定された場合にスローされます |

### 参照

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [SVGFEColorMatrixElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
