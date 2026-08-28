---
title: "SVGBuilderExtensions.SetPreserveAspectRatio"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions SetPreserveAspectRatio メソッド。SVG 要素の preserveAspectRatio 属性を設定します。"
type: docs
weight: 2020
url: /ja/net/aspose.svg.builder/svgbuilderextensions/setpreserveaspectratio/
---
## SVGBuilderExtensions.SetPreserveAspectRatio<TBuilder> method

SVG 要素の 'preserveAspectRatio' 属性を設定します。

```csharp
public static TBuilder SetPreserveAspectRatio<TBuilder>(this TBuilder builder, 
    AspectRatioAlign align, AspectRatioScaling meetOrSlice = AspectRatioScaling.Meet)
    where TBuilder : ISVGElementBuilder, IPreserveAspectRatioAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| align | アスペクト比の配置設定です。 |
| meetOrSlice | アスペクト比がどのように保持されるかを指定します（デフォルトは 'Meet'）。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [AspectRatioAlign](../../aspectratioalign/)
* enum [AspectRatioScaling](../../aspectratioscaling/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../../ipreserveaspectratioattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
