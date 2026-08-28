---
title: "SVGBuilderExtensions.OnError"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnError メソッド。要素のエラーイベントを処理するために onerror イベント属性を設定します。"
type: docs
weight: 1430
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onerror/
---
## SVGBuilderExtensions.OnError<TBuilder> method

'onerror' イベント属性を設定し、要素上のエラーイベントを処理します。

```csharp
public static TBuilder OnError<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, ICommonEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | エラーが発生したときに実行される JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICommonEventAttributeSetter](../../icommoneventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
