---
title: "SVGBuilderExtensions.Mask"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions Mask メソッド。カスタム mask 構成を使用して SVG 要素の mask 属性を設定します。"
type: docs
weight: 1150
url: /ja/net/aspose.svg.builder/svgbuilderextensions/mask/
---
## SVGBuilderExtensions.Mask<TBuilder> method

カスタムマスク設定を使用して、SVG要素の 'mask' 属性を設定します。

```csharp
public static TBuilder Mask<TBuilder>(this TBuilder builder, Action<MaskBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | mask を構成するデリゲートです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [MaskBuilder](../../maskbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
