---
title: "SVGBuilderExtensions.OnResize"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnResize メソッド。ウィンドウまたは要素のリサイズイベントを処理するために onresize イベント属性を設定します。"
type: docs
weight: 1720
url: /ja/net/aspose.svg.builder/svgbuilderextensions/onresize/
---
## SVGBuilderExtensions.OnResize<TBuilder> method

'onresize' イベント属性を設定し、ウィンドウまたは要素のサイズ変更イベントを処理します。

```csharp
public static TBuilder OnResize<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, ICommonEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | 要素またはウィンドウがリサイズされたときに実行される JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICommonEventAttributeSetter](../../icommoneventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
