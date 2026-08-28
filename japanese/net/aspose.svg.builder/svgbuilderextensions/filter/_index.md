---
title: "SVGBuilderExtensions.Filter"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions Filter メソッド。カスタム構成を使用して SVG 要素の filter 属性を設定します。"
type: docs
weight: 840
url: /ja/net/aspose.svg.builder/svgbuilderextensions/filter/
---
## SVGBuilderExtensions.Filter<TBuilder> method

カスタム構成を使用して SVG 要素の 'filter' 属性を設定します。

```csharp
public static TBuilder Filter<TBuilder>(this TBuilder builder, 
    Action<FilterValueListBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | FilterValueListBuilder を構成するデリゲート。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [FilterValueListBuilder](../../filtervaluelistbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
