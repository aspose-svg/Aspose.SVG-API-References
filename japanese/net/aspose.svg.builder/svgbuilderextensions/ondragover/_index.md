---
title: "SVGBuilderExtensions.OnDragOver"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnDragOver メソッド。アイテムが有効なドロップターゲット上にドラッグされたときの処理のために ondragover イベント属性を設定します。"
type: docs
weight: 1360
url: /ja/net/aspose.svg.builder/svgbuilderextensions/ondragover/
---
## SVGBuilderExtensions.OnDragOver<TBuilder> method

項目が有効なドロップターゲット上をドラッグすることを処理するために、'ondragover' イベント属性を設定します。

```csharp
public static TBuilder OnDragOver<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | 項目が有効なドロップターゲット上でドラッグされているときに実行される JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
