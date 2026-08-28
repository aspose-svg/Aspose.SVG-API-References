---
title: "SVGBuilderExtensions.OnProgress"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnProgress メソッド。進行中のプロセスの進捗を示すイベントを処理するために onprogress イベント属性を設定します。"
type: docs
weight: 1680
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onprogress/
---
## SVGBuilderExtensions.OnProgress<TBuilder> method

'onprogress' イベント属性を設定し、進行中のプロセスの進捗を示すイベントを処理します。

```csharp
public static TBuilder OnProgress<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | 進行中のプロセスの進捗を示すために実行する JavaScript 関数またはスクリプト。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
