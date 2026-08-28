---
title: "SVGBuilderExtensions.AddMarker"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddMarker メソッド。builder にマーカー要素の構成を追加します。"
type: docs
weight: 370
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addmarker/
---
## SVGBuilderExtensions.AddMarker<TBuilder> method

ビルダーに 'marker' 要素の構成を追加します。

```csharp
public static TBuilder AddMarker<TBuilder>(this TBuilder builder, 
    Action<SVGMarkerElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | 'marker' 要素の構成アクションです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGMarkerElementBuilder](../../svgmarkerelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
