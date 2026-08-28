---
title: "SVGBuilderExtensions.RepeatCount"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions RepeatCount メソッド。アニメーションが繰り返す回数を定義する repeatCount 属性を設定します。"
type: docs
weight: 1950
url: /ja/net/aspose.svg.builder/svgbuilderextensions/repeatcount/
---
## RepeatCount<TBuilder>(*this TBuilder, int*) {#repeatcount_1}

アニメーションが繰り返す回数を定義する 'repeatCount' 属性を設定します。

```csharp
public static TBuilder RepeatCount<TBuilder>(this TBuilder builder, int value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | アニメーションが繰り返す回数です。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RepeatCount<TBuilder>(*this TBuilder, [IndefiniteRepeat](../../indefiniterepeat/)*) {#repeatcount}

事前定義された列挙体を使用して、アニメーションの無期限の繰り返し回数を定義する 'repeatCount' 属性を設定します。

```csharp
public static TBuilder RepeatCount<TBuilder>(this TBuilder builder, IndefiniteRepeat value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | アニメーション用に事前定義された無期限の繰り返し回数です。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* enum [IndefiniteRepeat](../../indefiniterepeat/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
