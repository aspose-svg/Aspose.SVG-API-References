---
title: "SVGBuilderExtensions.OnLoadedMetadata"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnLoadedMetadata メソッド。メディアメタデータが読み込まれたときのイベント処理のために onloadedmetadata イベント属性を設定します。"
type: docs
weight: 1540
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onloadedmetadata/
---
## SVGBuilderExtensions.OnLoadedMetadata<TBuilder> method

'onloadedmetadata' イベント属性を設定し、メディアメタデータがロードされたときのイベントを処理します。

```csharp
public static TBuilder OnLoadedMetadata<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | メディアメタデータが読み込まれたときに実行される JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
