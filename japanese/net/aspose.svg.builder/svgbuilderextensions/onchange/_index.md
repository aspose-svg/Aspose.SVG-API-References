---
title: "SVGBuilderExtensions.OnChange"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnChange メソッド。要素の値の変化を処理するために onchange イベント属性を設定します。"
type: docs
weight: 1240
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onchange/
---
## SVGBuilderExtensions.OnChange<TBuilder> method

要素の値の変更を処理するために、'onchange' イベント属性を設定します。

```csharp
public static TBuilder OnChange<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | 要素の値が変化したときに実行する JavaScript 関数またはスクリプト。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
