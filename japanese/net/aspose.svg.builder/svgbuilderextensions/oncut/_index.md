---
title: "SVGBuilderExtensions.OnCut"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnCut メソッド。SVG 要素からコンテンツがカットされたときに実行されるスクリプトを定義する oncut イベント属性を設定します。"
type: docs
weight: 1290
url: /ja/net/aspose.svg.builder/svgbuilderextensions/oncut/
---
## SVGBuilderExtensions.OnCut<TBuilder> method

SVG 要素からコンテンツが切り取られたときに実行されるスクリプトを定義するために、'oncut' イベント属性を設定します。

```csharp
public static TBuilder OnCut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | カットイベント時に実行される JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
