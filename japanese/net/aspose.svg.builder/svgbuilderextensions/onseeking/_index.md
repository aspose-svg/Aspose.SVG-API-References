---
title: "SVGBuilderExtensions.OnSeeking"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnSeeking メソッド。メディアのシーク操作が開始されたときのイベント処理のために onseeking イベント属性を設定します。"
type: docs
weight: 1750
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onseeking/
---
## SVGBuilderExtensions.OnSeeking<TBuilder> method

'onseeking' イベント属性を設定し、メディアのシーク操作が開始されたときのイベントを処理します。

```csharp
public static TBuilder OnSeeking<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | シーク操作が開始されたときに実行される JavaScript 関数またはスクリプト。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
