---
title: "SVGBuilderExtensions.XlinkHref"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions XlinkHref メソッド。SVG 要素の xlinkhref 属性を設定します。この属性はリソースへの参照をリンクとして定義するために使用されます。"
type: docs
weight: 2370
url: /ja/net/aspose.svg.builder/svgbuilderextensions/xlinkhref/
---
## SVGBuilderExtensions.XlinkHref<TBuilder> method

SVG 要素の 'xlink:href' 属性を設定します。この属性はリソースへのリンク参照を定義するために使用されます。

```csharp
public static TBuilder XlinkHref<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IXLinkAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | リンク先リソースの URI。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IXLinkAttributeSetter](../../ixlinkattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
