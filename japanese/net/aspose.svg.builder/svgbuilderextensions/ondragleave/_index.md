---
title: "SVGBuilderExtensions.OnDragLeave"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnDragLeave メソッド。ドラッグされた項目が有効なドロップターゲットから離れることを処理するために ondragleave イベント属性を設定します。"
type: docs
weight: 1350
url: /ja/net/aspose.svg.builder/svgbuilderextensions/ondragleave/
---
## SVGBuilderExtensions.OnDragLeave<TBuilder> method

ドラッグされた項目が有効なドロップターゲットから離れることを処理するために、'ondragleave' イベント属性を設定します。

```csharp
public static TBuilder OnDragLeave<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | ドラッグされた項目が有効なドロップターゲットから離れたときに実行される JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
