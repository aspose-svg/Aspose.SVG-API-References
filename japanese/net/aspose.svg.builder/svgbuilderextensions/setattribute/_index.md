---
title: "SVGBuilderExtensions.SetAttribute"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions SetAttribute メソッド。SVG 要素に属性を設定します。このメソッドは、構築中の SVG 要素の属性を追加または変更するために使用されます。"
type: docs
weight: 2010
url: /ja/net/aspose.svg.builder/svgbuilderextensions/setattribute/
---
## SVGBuilderExtensions.SetAttribute<TBuilder> method

SVG 要素に属性を設定します。このメソッドは、構築中の SVG 要素の属性を追加または変更するために使用されます。

```csharp
public static TBuilder SetAttribute<TBuilder>(this TBuilder builder, string name, string value)
    where TBuilder : IAttributeSetter
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | 属性が設定される SVG 要素ビルダーです。 |
| 名前 | 設定する属性の名前です。 |
| value | 属性の値です。 |

### 戻り値

メソッドチェーン用の元の SVG 要素ビルダーです。

### 参照

* interface [IAttributeSetter](../../iattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
