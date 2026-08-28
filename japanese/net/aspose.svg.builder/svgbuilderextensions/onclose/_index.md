---
title: "SVGBuilderExtensions.OnClose"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnClose メソッド。ダイアログ要素のクローズ操作を処理するために onclose イベント属性を設定します。"
type: docs
weight: 1260
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onclose/
---
## SVGBuilderExtensions.OnClose<TBuilder> method

ダイアログ要素の閉じる操作を処理するために、'onclose' イベント属性を設定します。

```csharp
public static TBuilder OnClose<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | ダイアログが閉じられたときに実行される JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
