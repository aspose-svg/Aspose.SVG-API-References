---
title: "SVGBuilderExtensions.OnFocusOut"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnFocusOut メソッド。要素のフォーカスアウトイベントを処理するために onfocusout イベント属性を設定します。"
type: docs
weight: 1460
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onfocusout/
---
## SVGBuilderExtensions.OnFocusOut<TBuilder> method

'onfocusout' イベント属性を設定し、要素上のフォーカスアウトイベントを処理します。

```csharp
public static TBuilder OnFocusOut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | 要素がフォーカスを失ったときに実行される JavaScript 関数またはスクリプトで、通常は 'onblur' イベントの前に実行されます。 |

### 戻り値

チェーン用のビルダーインスタンス。

## 備考

要素がフォーカスを失いそうになると 'onfocusout' イベントが発生します。'onfocusin' と同様に、このイベントはバブリングをサポートし、子要素のフォーカス変化も検出できます。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
