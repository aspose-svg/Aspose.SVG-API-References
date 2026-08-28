---
title: "SVGBuilderExtensions.LengthAdjust"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions LengthAdjust メソッド。テキストコンテンツの長さ調整方法を設定します。"
type: docs
weight: 1090
url: /ja/net/aspose.svg.builder/svgbuilderextensions/lengthadjust/
---
## SVGBuilderExtensions.LengthAdjust<TBuilder> method

テキストコンテンツの長さ調整方法を設定します。

```csharp
public static TBuilder LengthAdjust<TBuilder>(this TBuilder builder, LengthAdjust value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | 長さ調整方法です。 |

### 戻り値

チェーン用のビルダーインスタンス。

## 備考

このメソッドは 'lengthAdjust' 属性を設定し、テキストの長さを間隔で調整するかスケーリングで調整するかを決定します。

### 参照

* enum [LengthAdjust](../../lengthadjust/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
