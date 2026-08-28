---
title: "SVGBuilderExtensions.OnSuspend"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnSuspend メソッド。メディアデータの読み込みが中断されたときのイベントを処理するために onsuspend イベント属性を設定します。"
type: docs
weight: 1800
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onsuspend/
---
## SVGBuilderExtensions.OnSuspend<TBuilder> method

'onsuspend' イベント属性を設定し、メディアデータの読み込みが一時停止されたときのイベントを処理します。

```csharp
public static TBuilder OnSuspend<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | メディアデータの読み込みが中断されたときに実行される JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
