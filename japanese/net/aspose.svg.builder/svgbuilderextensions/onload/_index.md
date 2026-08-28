---
title: "SVGBuilderExtensions.OnLoad"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnLoad メソッド。要素上のロードイベントを処理するために onload イベント属性を設定します。"
type: docs
weight: 1520
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onload/
---
## SVGBuilderExtensions.OnLoad<TBuilder> method

'onload' イベント属性を設定し、要素上のロードイベントを処理します。

```csharp
public static TBuilder OnLoad<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | 要素の読み込みが完了したときに実行される JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
