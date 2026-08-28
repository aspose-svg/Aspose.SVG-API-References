---
title: "SVGBuilderExtensions.KeyTimes"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions KeyTimes メソッド。キー値が適用される時間を定義する keyTimes 属性を設定します。"
type: docs
weight: 1070
url: /ja/net/aspose.svg.builder/svgbuilderextensions/keytimes/
---
## SVGBuilderExtensions.KeyTimes<TBuilder> method

'keyTimes' 属性を設定し、キー値が適用される時刻を定義します。

```csharp
public static TBuilder KeyTimes<TBuilder>(this TBuilder builder, params double[] keyTimes)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| keyTimes | アニメーションのキー時間の配列です。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
