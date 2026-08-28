---
title: "SVGBuilderExtensions.AddSvg"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddSvg メソッド。ビルダーに SVG スケーラブルベクターグラフィックス要素の構成を追加します。"
type: docs
weight: 500
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addsvg/
---
## SVGBuilderExtensions.AddSvg<TBuilder> method

ビルダーに 'svg'（スケーラブルベクターグラフィックス）要素の構成を追加します。

```csharp
public static TBuilder AddSvg<TBuilder>(this TBuilder builder, 
    Action<SVGSVGElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | ‘svg’ 要素の構成アクションです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGSVGElementBuilder](../../svgsvgelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
