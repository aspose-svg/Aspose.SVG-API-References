---
title: "SVGBuilderExtensions.OnPaste"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnPaste メソッド。SVG 要素にコンテンツが貼り付けられたときに実行されるスクリプトを定義する onpaste イベント属性を設定します。"
type: docs
weight: 1640
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onpaste/
---
## SVGBuilderExtensions.OnPaste<TBuilder> method

'onpaste' イベント属性を設定し、コンテンツが SVG 要素に貼り付けられたときに実行されるスクリプトを定義します。

```csharp
public static TBuilder OnPaste<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | 貼り付けイベントで実行される JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
