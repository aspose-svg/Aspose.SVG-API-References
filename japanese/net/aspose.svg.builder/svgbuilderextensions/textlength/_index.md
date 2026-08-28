---
title: "SVGBuilderExtensions.TextLength"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions TextLength メソッド。テキストコンテンツの正確な長さを設定します。"
type: docs
weight: 2220
url: /ja/net/aspose.svg.builder/svgbuilderextensions/textlength/
---
## SVGBuilderExtensions.TextLength<TBuilder> method

テキストコンテンツの正確な長さを設定します。

```csharp
public static TBuilder TextLength<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | テキストの長さです。 |
| type | 値の長さ単位のタイプです。 |

### 戻り値

チェーン用のビルダーインスタンス。

## 備考

このメソッドは 'textLength' 属性を設定し、テキストコンテンツの希望する長さを指定します。これにより、自然なテキスト長さを上書きする可能性があります。

### 参照

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
