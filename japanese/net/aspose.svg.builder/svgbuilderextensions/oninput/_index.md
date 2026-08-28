---
title: "SVGBuilderExtensions.OnInput"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnInput メソッド。要素上の入力イベントを処理するための oninput イベント属性を設定します"
type: docs
weight: 1470
url: /ja/net/aspose.svg.builder/svgbuilderextensions/oninput/
---
## SVGBuilderExtensions.OnInput<TBuilder> method

'oninput' イベント属性を設定し、要素上の入力イベントを処理します。

```csharp
public static TBuilder OnInput<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | 要素がユーザー入力を受け取ったときに実行される JavaScript 関数またはスクリプト。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
