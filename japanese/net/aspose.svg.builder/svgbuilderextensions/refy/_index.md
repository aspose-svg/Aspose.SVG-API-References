---
title: "SVGBuilderExtensions.RefY"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions RefY メソッド。SVG 要素の refY 属性を設定します"
type: docs
weight: 1940
url: /ja/net/aspose.svg.builder/svgbuilderextensions/refy/
---
## RefY<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#refy_1}

SVG 要素の 'refY' 属性を設定します。

```csharp
public static TBuilder RefY<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRefCoordinatesAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | 参照 Y 座標。 |
| type | 長さ単位のタイプ（デフォルトはピクセルです）。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRefCoordinatesAttributeSetter](../../irefcoordinatesattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RefY<TBuilder>(*this TBuilder, [VerticalPosition](../../verticalposition/)*) {#refy}

事前定義された垂直位置を使用して SVG 要素の 'refY' 属性を設定します。

```csharp
public static TBuilder RefY<TBuilder>(this TBuilder builder, VerticalPosition value)
    where TBuilder : ISVGElementBuilder, IRefCoordinatesAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| value | 事前定義された垂直位置。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [VerticalPosition](../../verticalposition/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRefCoordinatesAttributeSetter](../../irefcoordinatesattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
