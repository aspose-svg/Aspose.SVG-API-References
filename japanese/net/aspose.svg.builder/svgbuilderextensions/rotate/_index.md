---
title: "SVGBuilderExtensions.Rotate"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions Rotate メソッド。テキストコンテンツの個々の文字またはセグメントの回転角度を設定します"
type: docs
weight: 2000
url: /ja/net/aspose.svg.builder/svgbuilderextensions/rotate/
---
## Rotate<TBuilder>(*this TBuilder, params double[]*) {#rotate_1}

テキスト内容の個々の文字またはセグメントの回転角度を設定します。

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| values | 度数で表された回転角度の配列。 |

### 戻り値

チェーン用のビルダーインスタンス。

## 備考

このメソッドは 'rotate' 属性に複数の値を設定し、各文字またはテキストセグメントの個別回転を可能にします。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Rotate<TBuilder>(*this TBuilder, double*) {#rotate}

テキスト全体の回転角度を単一に設定します。

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, double value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | 度数での回転角度。 |

### 戻り値

チェーン用のビルダーインスタンス。

## 備考

このメソッドは 'rotate' 属性に単一の値を設定し、すべてのテキストコンテンツに同じ回転角度を適用します。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
