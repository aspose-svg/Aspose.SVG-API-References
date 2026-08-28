---
title: "SVGBuilderExtensions.Dur"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions Dur メソッド。アニメーションの期間を指定する dur 属性を設定します。"
type: docs
weight: 760
url: /ja/net/aspose.svg.builder/svgbuilderextensions/dur/
---
## Dur<TBuilder>(*this TBuilder, TimeSpan*) {#dur_1}

'dur' 属性を設定し、アニメーションの期間を指定します。

```csharp
public static TBuilder Dur<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| 期間 | アニメーションの期間です。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dur<TBuilder>(*this TBuilder, [Dur](../../dur/)*) {#dur}

'dur' 属性を設定し、アニメーションの事前定義された期間タイプを指定します。

```csharp
public static TBuilder Dur<TBuilder>(this TBuilder builder, Dur value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | アニメーション用に事前定義された期間タイプです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [Dur](../../dur/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
