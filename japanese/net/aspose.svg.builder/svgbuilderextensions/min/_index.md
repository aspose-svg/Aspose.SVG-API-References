---
title: "SVGBuilderExtensions.Min"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions Min メソッド。アニメーションの最小期間を指定する min 属性を設定します"
type: docs
weight: 1170
url: /ja/net/aspose.svg.builder/svgbuilderextensions/min/
---
## Min<TBuilder>(*this TBuilder, TimeSpan*) {#min_1}

アニメーションの最小期間を指定するために、'min' 属性を設定します。

```csharp
public static TBuilder Min<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| 期間 | アニメーションの最小期間。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Min<TBuilder>(*this TBuilder, [Media](../../media/)*) {#min}

メディアに基づくアニメーションの最小期間条件を指定するために、'min' 属性を設定します。

```csharp
public static TBuilder Min<TBuilder>(this TBuilder builder, Media value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | アニメーションのメディア関連の最小期間条件。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [Media](../../media/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
