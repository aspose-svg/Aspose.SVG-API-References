---
title: "SVGBuilderExtensions.OnInvalid"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnInvalid メソッド。フォーム要素の無効なイベントを処理するための oninvalid イベント属性を設定します。"
type: docs
weight: 1480
url: /ja/net/aspose.svg.builder/svgbuilderextensions/oninvalid/
---
## SVGBuilderExtensions.OnInvalid<TBuilder> method

'oninvalid' イベント属性を設定し、フォーム要素上の無効イベントを処理します。

```csharp
public static TBuilder OnInvalid<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | 要素の値が無効なときに実行される JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
