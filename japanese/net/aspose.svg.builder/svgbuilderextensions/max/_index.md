---
title: "SVGBuilderExtensions.Max"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions Max メソッド。アニメーションの最大期間を指定する max 属性を設定します。"
type: docs
weight: 1160
url: /ja/net/aspose.svg.builder/svgbuilderextensions/max/
---
## Max<TBuilder>(*this TBuilder, TimeSpan*) {#max_1}

アニメーションの最大期間を指定するために、'max' 属性を設定します。

```csharp
public static TBuilder Max<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| 期間 | アニメーションの最大期間です。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Max<TBuilder>(*this TBuilder, [Media](../../media/)*) {#max}

アニメーションの事前定義された最大期間条件を指定するために、'max' 属性を設定します。

```csharp
public static TBuilder Max<TBuilder>(this TBuilder builder, Media value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | アニメーションの事前定義された最大期間条件です。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [Media](../../media/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
