---
title: "SVGBuilderExtensions.OnToggle"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions OnToggle メソッド。details 要素のようなコントロールがユーザーによってトグルされたときのイベントを処理するために ontoggle イベント属性を設定します。"
type: docs
weight: 1820
url: /ja/net/aspose.svg.builder/svgbuilderextensions/ontoggle/
---
## SVGBuilderExtensions.OnToggle<TBuilder> method

'ontoggle' イベント属性を設定し、ユーザーが `details` 要素のようなコントロールを切り替えたときのイベントを処理します。

```csharp
public static TBuilder OnToggle<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | SVG 要素ビルダーです。 |
| value | コントロールがトグルされたときに実行される JavaScript 関数またはスクリプトです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
