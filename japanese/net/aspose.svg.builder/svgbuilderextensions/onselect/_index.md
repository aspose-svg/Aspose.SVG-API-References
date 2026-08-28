---
title: "SVGBuilderExtensions.OnSelect"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions の OnSelect メソッド。要素上のテキスト選択イベントを処理するための onselect イベント属性を設定します。"
type: docs
weight: 1760
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onselect/
---
## SVGBuilderExtensions.OnSelect<TBuilder> method

'onselect' イベント属性を設定し、要素上のテキスト選択イベントを処理します。

```csharp
public static TBuilder OnSelect<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | 要素内でテキストが選択されたときに実行される JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
