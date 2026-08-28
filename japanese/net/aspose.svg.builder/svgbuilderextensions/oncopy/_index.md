---
title: "SVGBuilderExtensions.OnCopy"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnCopy メソッド。SVG 要素からコンテンツがコピーされたときに実行されるスクリプトを定義する oncopy イベント属性を設定します。"
type: docs
weight: 1270
url: /ja/net/aspose.svg.builder/svgbuilderextensions/oncopy/
---
## SVGBuilderExtensions.OnCopy<TBuilder> method

SVG 要素からコンテンツがコピーされたときに実行されるスクリプトを定義するために、'oncopy' イベント属性を設定します。

```csharp
public static TBuilder OnCopy<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | コピーイベント時に実行される JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
