---
title: "SVGBuilderExtensions.MarkerMid"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions MarkerMid メソッド。パスの中間点にマーカーを指定するための SVG 要素の marker-mid 属性を設定します。"
type: docs
weight: 1130
url: /ja/net/aspose.svg.builder/svgbuilderextensions/markermid/
---
## MarkerMid<TBuilder>(*this TBuilder, string*) {#markermid_1}

SVG要素の 'marker-mid' 属性を設定し、パスの中間点にマーカーを指定します。

```csharp
public static TBuilder MarkerMid<TBuilder>(this TBuilder builder, string markerId)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| markerId | 使用するマーカーの ID です。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## MarkerMid<TBuilder>(*this TBuilder, [MarkerPos](../../markerpos/)*) {#markermid}

事前定義されたマーカー位置を使用して、SVG要素の 'marker-mid' 属性を設定します。

```csharp
public static TBuilder MarkerMid<TBuilder>(this TBuilder builder, MarkerPos value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | 設定するマーカーの位置値です。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [MarkerPos](../../markerpos/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
