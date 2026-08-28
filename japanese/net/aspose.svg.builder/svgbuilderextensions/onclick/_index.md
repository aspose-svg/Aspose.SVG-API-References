---
title: "SVGBuilderExtensions.OnClick"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnClick メソッド。要素のクリックイベントを処理するために onclick イベント属性を設定します"
type: docs
weight: 1250
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onclick/
---
## SVGBuilderExtensions.OnClick<TBuilder> method

要素上のクリックイベントを処理するために、'onclick' イベント属性を設定します。

```csharp
public static TBuilder OnClick<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | クリックイベントで実行する JavaScript 関数またはスクリプト。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
