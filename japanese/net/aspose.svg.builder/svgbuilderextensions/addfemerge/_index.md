---
title: "SVGBuilderExtensions.AddFeMerge"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddFeMerge メソッド。ビルダーに feMerge 要素の構成を追加します。この要素は、フィルタ効果を順次ではなく同時に適用できるようにします。"
type: docs
weight: 240
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addfemerge/
---
## SVGBuilderExtensions.AddFeMerge<TBuilder> method

ビルダーに 'feMerge' 要素の構成を追加します。この要素はフィルター効果を順次ではなく同時に適用できるようにします。

```csharp
public static TBuilder AddFeMerge<TBuilder>(this TBuilder builder, 
    Action<SVGFEMergeElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | ‘feMerge’ 要素の構成アクションです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGFEMergeElementBuilder](../../svgfemergeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
