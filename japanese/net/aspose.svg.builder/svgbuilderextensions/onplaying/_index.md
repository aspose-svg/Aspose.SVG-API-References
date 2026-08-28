---
title: "SVGBuilderExtensions.OnPlaying"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnPlaying メソッド。メディアがバッファリングのために一時停止または停止された後、再び再生中になる際のイベントを処理するために onplaying イベント属性を設定します。"
type: docs
weight: 1670
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onplaying/
---
## SVGBuilderExtensions.OnPlaying<TBuilder> method

'onplaying' イベント属性を設定し、メディアが一時停止またはバッファリングのために停止された後、積極的に再生されているときのイベントを処理します。

```csharp
public static TBuilder OnPlaying<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | メディアが再生中のときに実行される JavaScript 関数またはスクリプト。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
