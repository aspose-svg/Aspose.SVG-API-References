---
title: "SVGBuilderExtensions.MarkerEnd"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions MarkerEnd メソッド。パスの終点にマーカーを指定する marker-end 属性を SVG 要素に設定します。"
type: docs
weight: 1120
url: /ja/net/aspose.svg.builder/svgbuilderextensions/markerend/
---
## MarkerEnd<TBuilder>(*this TBuilder, string*) {#markerend_1}

SVG要素の 'marker-end' 属性を設定し、パスの終点にマーカーを指定します。

```csharp
public static TBuilder MarkerEnd<TBuilder>(this TBuilder builder, string markerId)
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

## MarkerEnd<TBuilder>(*this TBuilder, [MarkerPos](../../markerpos/)*) {#markerend}

事前定義されたマーカー位置を使用して、SVG要素の 'marker-end' 属性を設定します。

```csharp
public static TBuilder MarkerEnd<TBuilder>(this TBuilder builder, MarkerPos value)
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
