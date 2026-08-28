---
title: "SVGBuilderExtensions.ClipPath"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions ClipPath メソッド。SVG 要素の clip-path 属性を設定します。"
type: docs
weight: 650
url: /ja/net/aspose.svg.builder/svgbuilderextensions/clippath/
---
## SVGBuilderExtensions.ClipPath<TBuilder> method

SVG 要素の 'clip-path' 属性を設定します。

```csharp
public static TBuilder ClipPath<TBuilder>(this TBuilder builder, Action<ClipPathBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | clip パスを構成するためのデリゲートです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [ClipPathBuilder](../../clippathbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
