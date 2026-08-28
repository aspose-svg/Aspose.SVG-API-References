---
title: "SVGBuilderExtensions.FloodColor"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions FloodColor メソッド。System.Drawing のカラーを使用して SVG 要素の flood-color 属性を設定します。"
type: docs
weight: 850
url: /ja/net/aspose.svg.builder/svgbuilderextensions/floodcolor/
---
## FloodColor<TBuilder>(*this TBuilder, Color*) {#floodcolor_1}

System.Drawing のカラーを使用して SVG 要素の 'flood-color' 属性を設定します。

```csharp
public static TBuilder FloodColor<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| colorValue | 洪水色として設定する色。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## FloodColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#floodcolor}

カスタムカラー構成を使用して SVG 要素の 'flood-color' 属性を設定します。

```csharp
public static TBuilder FloodColor<TBuilder>(this TBuilder builder, Action<ColorBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | ColorBuilder を構成するためのデリゲート。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [ColorBuilder](../../colorbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
