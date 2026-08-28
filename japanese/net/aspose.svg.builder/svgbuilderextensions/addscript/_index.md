---
title: "SVGBuilderExtensions.AddScript"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGBuilderExtensions AddScript メソッド。ビルダーに script 要素の構成を追加します。"
type: docs
weight: 460
url: /ja/net/aspose.svg.builder/svgbuilderextensions/addscript/
---
## SVGBuilderExtensions.AddScript<TBuilder> method

ビルダーに 'script' 要素の構成を追加します。

```csharp
public static TBuilder AddScript<TBuilder>(this TBuilder builder, 
    Action<SVGScriptElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeContentElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TBuilder | SVG 要素ビルダーの型です。 |
| ビルダー | ビルダー インスタンス。 |
| 構成 | 'script' 要素の構成アクションです。 |

### 戻り値

チェーン用のビルダーインスタンス。

### 参照

* class [SVGScriptElementBuilder](../../svgscriptelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeContentElementBuilder](../../ishapecontentelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
