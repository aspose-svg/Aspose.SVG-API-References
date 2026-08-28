---
title: "SVGBuilderExtensions.Type"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions Type メソッド。コンポーネント転送関数要素の type 属性を設定します。"
type: docs
weight: 2270
url: /ja/net/aspose.svg.builder/svgbuilderextensions/type/
---
## SVGBuilderExtensions.Type<TBuilder> method

コンポーネント転送関数要素の 'type' 属性を設定します。

```csharp
public static TBuilder Type<TBuilder>(this TBuilder builder, ComponentTransferType type)
    where TBuilder : ISVGElementBuilder, ITransferFunctionAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| type | コンポーネント転送関数のタイプ（例：linear、gamma）。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [ComponentTransferType](../../componenttransfertype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITransferFunctionAttributeSetter](../../itransferfunctionattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
