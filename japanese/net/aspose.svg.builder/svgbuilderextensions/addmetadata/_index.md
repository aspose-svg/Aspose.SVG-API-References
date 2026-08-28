---
title: "SVGBuilderExtensions.AddMetadata"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddMetadata メソッド。ビルダーに metadata 要素の構成を追加します。metadata 要素は SVG コンテンツにメタデータを追加するために使用されます。"
type: docs
weight: 390
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addmetadata/
---
## SVGBuilderExtensions.AddMetadata<TBuilder,TElement> method

ビルダーに 'metadata' 要素の構成を追加します。'metadata' 要素は SVG コンテンツにメタデータを追加するために使用されます。

```csharp
public static TBuilder AddMetadata<TBuilder, TElement>(this TBuilder builder, 
    Action<SVGMetadataElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| TElement | SVG モデル内の 'metadata' 要素を表す型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | 'metadata' 要素の構成アクションです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGMetadataElementBuilder](../../svgmetadataelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
