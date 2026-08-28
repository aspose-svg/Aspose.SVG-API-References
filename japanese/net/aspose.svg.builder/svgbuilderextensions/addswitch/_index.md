---
title: "SVGBuilderExtensions.AddSwitch"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddSwitch メソッド。ビルダーに switch 要素の構成を追加します。"
type: docs
weight: 510
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addswitch/
---
## SVGBuilderExtensions.AddSwitch<TBuilder> method

ビルダーに 'switch' 要素の構成を追加します。

```csharp
public static TBuilder AddSwitch<TBuilder>(this TBuilder builder, 
    Action<SVGSwitchElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | 'switch' 要素の構成アクション。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGSwitchElementBuilder](../../svgswitchelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
