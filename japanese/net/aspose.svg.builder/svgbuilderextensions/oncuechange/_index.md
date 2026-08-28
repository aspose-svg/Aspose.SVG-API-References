---
title: "SVGBuilderExtensions.OnCueChange"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnCueChange メソッド。テキストトラックのアクティブキューの変化を処理するために oncuechange イベント属性を設定します。"
type: docs
weight: 1280
url: /ja/net/aspose.svg.builder/svgbuilderextensions/oncuechange/
---
## SVGBuilderExtensions.OnCueChange<TBuilder> method

テキストトラックのアクティブキューの変更を処理するために、'oncuechange' イベント属性を設定します。

```csharp
public static TBuilder OnCueChange<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | テキストトラックのアクティブキューが変化したときに実行される JavaScript 関数またはスクリプト。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
