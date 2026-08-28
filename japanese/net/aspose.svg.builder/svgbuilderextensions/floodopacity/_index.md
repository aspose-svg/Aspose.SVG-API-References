---
title: "SVGBuilderExtensions.FloodOpacity"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions FloodOpacity メソッド。SVG 要素の flood-opacity 属性を設定します。値は 0.0（完全に透明）から 1.0（完全に不透明）の範囲でなければなりません。"
type: docs
weight: 860
url: /ja/net/aspose.svg.builder/svgbuilderextensions/floodopacity/
---
## SVGBuilderExtensions.FloodOpacity<TBuilder> method

SVG 要素の 'flood-opacity' 属性を設定します。値は 0.0（完全に透明）から 1.0（完全に不透明）の間でなければなりません。

```csharp
public static TBuilder FloodOpacity<TBuilder>(this TBuilder builder, double opacity)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| opacity | 設定する不透明度の値。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 不透明度が有効範囲外の場合にスローされます。 |

### 参照

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
