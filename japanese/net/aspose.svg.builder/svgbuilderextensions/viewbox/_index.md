---
title: "SVGBuilderExtensions.ViewBox"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions ViewBox メソッド。SVG 要素の viewBox 属性を設定します"
type: docs
weight: 2300
url: /ja/net/aspose.svg.builder/svgbuilderextensions/viewbox/
---
## SVGBuilderExtensions.ViewBox<TBuilder> method

SVG 要素の 'viewBox' 属性を設定します。

```csharp
public static TBuilder ViewBox<TBuilder>(this TBuilder builder, double minX, double minY, 
    double width, double height)
    where TBuilder : ISVGElementBuilder, IViewBoxAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| minX | viewBox の最小 X 座標です。 |
| minY | viewBox の最小 Y 座標です。 |
| width | viewBox の幅です。 |
| height | viewBox の高さです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IViewBoxAttributeSetter](../../iviewboxattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
