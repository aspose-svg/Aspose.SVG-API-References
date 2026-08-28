---
title: "SVGBuilderExtensions.OnDragExit"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnDragExit メソッド。ドラッグされた項目が有効なドロップターゲットから離れたときの処理のために ondragexit イベント属性を設定します。"
type: docs
weight: 1340
url: /ja/net/aspose.svg.builder/svgbuilderextensions/ondragexit/
---
## SVGBuilderExtensions.OnDragExit<TBuilder> method

ドラッグされた項目が有効なドロップターゲットから出ることを処理するために、'ondragexit' イベント属性を設定します。

```csharp
public static TBuilder OnDragExit<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | ドラッグされた項目が有効なドロップターゲットを離れたときに実行する JavaScript 関数またはスクリプト。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
