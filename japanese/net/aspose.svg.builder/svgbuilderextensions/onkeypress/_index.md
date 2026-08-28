---
title: "SVGBuilderExtensions.OnKeyPress"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnKeyPress メソッド。要素上のキー押下イベントを処理するために onkeypress イベント属性を設定します。"
type: docs
weight: 1500
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onkeypress/
---
## SVGBuilderExtensions.OnKeyPress<TBuilder> method

'onkeypress' イベント属性を設定し、要素上のキー入力イベントを処理します。

```csharp
public static TBuilder OnKeyPress<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | キーが押下され、離されたときに実行される JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
