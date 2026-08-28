---
title: "SVGBuilderExtensions.TextDecoration"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions TextDecoration メソッド。テキストに追加される装飾を定義する SVG 要素の text-decoration 属性を設定します。"
type: docs
weight: 2210
url: /ja/net/aspose.svg.builder/svgbuilderextensions/textdecoration/
---
## SVGBuilderExtensions.TextDecoration<TBuilder> method

SVG 要素の 'text-decoration' 属性を設定し、テキストに追加される装飾を定義します。

```csharp
public static TBuilder TextDecoration<TBuilder>(this TBuilder builder, bool underline = false, 
    bool overline = false, bool lineThrough = false, bool blink = false)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| underline | テキストに下線を付けるかどうかを指定します。 |
| overline | テキストにオーバーラインを付けるかどうかを指定します。 |
| lineThrough | テキストに取り消し線を付けるかどうかを指定します。 |
| blink | テキストを点滅させるかどうかを指定します（使用は推奨されません）。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
