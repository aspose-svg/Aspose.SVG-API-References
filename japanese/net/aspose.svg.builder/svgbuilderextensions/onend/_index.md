---
title: "SVGBuilderExtensions.OnEnd"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnEnd メソッド。アニメーションの終了時に実行されるスクリプトを定義する onend 属性を設定します。"
type: docs
weight: 1410
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onend/
---
## SVGBuilderExtensions.OnEnd<TBuilder> method

'onend' 属性を設定し、アニメーションの終了時に実行されるスクリプトを定義します。

```csharp
public static TBuilder OnEnd<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IAnimationEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | アニメーションが終了したときに実行されるスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationEventAttributeSetter](../../ianimationeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
