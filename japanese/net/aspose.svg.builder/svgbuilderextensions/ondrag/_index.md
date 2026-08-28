---
title: "SVGBuilderExtensions.OnDrag"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnDrag メソッド。要素上のドラッグ操作を処理するための ondrag イベント属性を設定します"
type: docs
weight: 1310
url: /ja/net/aspose.svg.builder/svgbuilderextensions/ondrag/
---
## SVGBuilderExtensions.OnDrag<TBuilder> method

要素上のドラッグ操作を処理するために、'ondrag' イベント属性を設定します。

```csharp
public static TBuilder OnDrag<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | ドラッグ操作中に実行する JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
