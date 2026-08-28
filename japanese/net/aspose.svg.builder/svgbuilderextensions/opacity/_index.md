---
title: "SVGBuilderExtensions.Opacity"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions Opacity メソッド。SVG 要素の透明度レベルを定義する opacity 属性を設定します。"
type: docs
weight: 1860
url: /ja/net/aspose.svg.builder/svgbuilderextensions/opacity/
---
## SVGBuilderExtensions.Opacity<TBuilder> method

SVG 要素の透明度レベルを定義する 'opacity' 属性を設定します。

```csharp
public static TBuilder Opacity<TBuilder>(this TBuilder builder, double opacity)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| opacity | opacity 値 (完全に透明な場合は 0.0、完全に不透明な場合は 1.0)です。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
