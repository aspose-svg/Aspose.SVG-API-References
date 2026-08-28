---
title: "SVGBuilderExtensions.OnDragEnter"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnDragEnter メソッド。ドラッグされた項目が有効なドロップターゲットに入ったときの処理のために ondragenter イベント属性を設定します。"
type: docs
weight: 1330
url: /ja/net/aspose.svg.builder/svgbuilderextensions/ondragenter/
---
## SVGBuilderExtensions.OnDragEnter<TBuilder> method

ドラッグされた項目が有効なドロップターゲットに入ることを処理するために、'ondragenter' イベント属性を設定します。

```csharp
public static TBuilder OnDragEnter<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | ドラッグされた項目が有効なドロップターゲットに入ったときに実行される JavaScript 関数またはスクリプト。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
