---
title: "SVGBuilderExtensions.OnDrop"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnDrop メソッド。アイテムが有効なドロップターゲットにドロップされたときの処理のために ondrop イベント属性を設定します"
type: docs
weight: 1380
url: /ja/net/aspose.svg.builder/svgbuilderextensions/ondrop/
---
## SVGBuilderExtensions.OnDrop<TBuilder> method

項目が有効なドロップターゲットにドロップされることを処理するために、'ondrop' イベント属性を設定します。

```csharp
public static TBuilder OnDrop<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | アイテムが有効なドロップターゲットにドロップされたときに実行される JavaScript 関数またはスクリプト。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
