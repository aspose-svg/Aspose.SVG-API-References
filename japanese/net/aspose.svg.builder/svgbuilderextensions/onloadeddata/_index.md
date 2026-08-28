---
title: "SVGBuilderExtensions.OnLoadedData"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnLoadedData メソッド。メディアデータがロードされたときのイベントを処理するための onloadeddata イベント属性を設定します。"
type: docs
weight: 1530
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onloadeddata/
---
## SVGBuilderExtensions.OnLoadedData<TBuilder> method

'onloadeddata' イベント属性を設定し、メディアデータがロードされたときのイベントを処理します。

```csharp
public static TBuilder OnLoadedData<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | メディアデータがロードされたときに実行される JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
