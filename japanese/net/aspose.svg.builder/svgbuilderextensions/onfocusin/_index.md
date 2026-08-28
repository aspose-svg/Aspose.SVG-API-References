---
title: "SVGBuilderExtensions.OnFocusIn"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnFocusIn メソッド。要素のフォーカスインイベントを処理するための onfocusin イベント属性を設定します。"
type: docs
weight: 1450
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onfocusin/
---
## SVGBuilderExtensions.OnFocusIn<TBuilder> method

'onfocusin' イベント属性を設定し、要素上のフォーカスインイベントを処理します。

```csharp
public static TBuilder OnFocusIn<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | 要素がフォーカスを受け取ったときに実行される JavaScript 関数またはスクリプトで、通常は 'onfocus' イベントの前に実行されます。 |

### 戻り値

チェーン用のビルダーインスタンス。

## 備考

'onfocusin' イベントは要素がフォーカスを受け取ろうとしたときに発生します。このイベントは 'onfocus' と異なり、バブリングをサポートし、子要素のフォーカス変化も検出できます。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
