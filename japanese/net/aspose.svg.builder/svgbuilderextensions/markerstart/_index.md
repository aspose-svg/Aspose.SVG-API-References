---
title: "SVGBuilderExtensions.MarkerStart"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions MarkerStart メソッド。パスの開始位置にマーカーを指定する marker-start 属性を SVG 要素に設定します"
type: docs
weight: 1140
url: /ja/net/aspose.svg.builder/svgbuilderextensions/markerstart/
---
## MarkerStart<TBuilder>(*this TBuilder, string*) {#markerstart_1}

SVG要素の 'marker-start' 属性を設定し、パスの開始点にマーカーを指定します。

```csharp
public static TBuilder MarkerStart<TBuilder>(this TBuilder builder, string markerId)
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

## MarkerStart<TBuilder>(*this TBuilder, [MarkerPos](../../markerpos/)*) {#markerstart}

事前定義されたマーカー位置を使用して、SVG要素の 'marker-start' 属性を設定します。

```csharp
public static TBuilder MarkerStart<TBuilder>(this TBuilder builder, MarkerPos value)
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
