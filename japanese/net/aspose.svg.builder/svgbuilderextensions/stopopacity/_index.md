---
title: "SVGBuilderExtensions.StopOpacity"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions StopOpacity メソッド。SVG 要素のグラデーションストップにおける不透明度を定義する stop-opacity 属性を設定します。"
type: docs
weight: 2070
url: /ja/net/aspose.svg.builder/svgbuilderextensions/stopopacity/
---
## SVGBuilderExtensions.StopOpacity<TBuilder> method

SVG 要素の 'stop-opacity' 属性を設定し、グラデーションストップでの不透明度を定義します。

```csharp
public static TBuilder StopOpacity<TBuilder>(this TBuilder builder, double opacity)
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
