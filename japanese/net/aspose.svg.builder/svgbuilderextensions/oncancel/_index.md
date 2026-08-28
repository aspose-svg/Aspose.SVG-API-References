---
title: "SVGBuilderExtensions.OnCancel"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnCancel メソッド。ユーザーのキャンセル操作を処理するために oncancel イベント属性を設定します。"
type: docs
weight: 1210
url: /ja/net/aspose.svg.builder/svgbuilderextensions/oncancel/
---
## SVGBuilderExtensions.OnCancel<TBuilder> method

ユーザーのキャンセル操作を処理するために、'oncancel' イベント属性を設定します。

```csharp
public static TBuilder OnCancel<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | キャンセルイベント時に実行される JavaScript 関数またはスクリプト。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
