---
title: "SVGBuilderExtensions.OnAbort"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnAbort メソッド。SVG ドキュメントの読み込みが中止されたときに実行されるスクリプトを定義する onabort イベント属性を設定します。"
type: docs
weight: 1190
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onabort/
---
## SVGBuilderExtensions.OnAbort<TBuilder> method

SVG ドキュメントの読み込みが中止されたときに実行されるスクリプトを定義するために、'onabort' イベント属性を設定します。

```csharp
public static TBuilder OnAbort<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | ドキュメントの読み込みが中止されたときに実行される JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentEventAttributeSetter](../../idocumenteventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
