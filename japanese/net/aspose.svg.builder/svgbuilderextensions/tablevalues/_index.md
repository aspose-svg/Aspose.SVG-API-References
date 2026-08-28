---
title: "SVGBuilderExtensions.TableValues"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions TableValues メソッド。コンポーネント転送関数要素の tableValues 属性を設定します。"
type: docs
weight: 2190
url: /ja/net/aspose.svg.builder/svgbuilderextensions/tablevalues/
---
## SVGBuilderExtensions.TableValues<TBuilder> method

コンポーネント転送関数要素の 'tableValues' 属性を設定します。

```csharp
public static TBuilder TableValues<TBuilder>(this TBuilder builder, params double[] values)
    where TBuilder : ISVGElementBuilder, ITransferFunctionAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| values | 転送関数のテーブル値です。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITransferFunctionAttributeSetter](../../itransferfunctionattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
