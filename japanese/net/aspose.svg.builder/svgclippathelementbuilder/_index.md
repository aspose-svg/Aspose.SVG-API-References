---
title: "SVGClipPathElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGClipPathElementBuilder クラス。クリッピング パスを定義するために使用される SVG clipPath 要素を構築するビルダー クラス。clipPath 要素内のコンテンツ構築を可能にし、SVG の clipPath 要素に固有のさまざまな属性を設定するメソッドを提供します。"
type: docs
weight: 1130
url: /ja/net/aspose.svg.builder/svgclippathelementbuilder/
---
## SVGClipPathElementBuilder class

クリッピングパスを定義するために使用される SVG の 'clipPath' 要素を構築するビルダー クラスです。'clipPath' 要素内のコンテンツ構築を可能にし、SVG の 'clipPath' 要素固有のさまざまな属性を設定するメソッドを提供します。

```csharp
public class SVGClipPathElementBuilder : SVGElementBuilder<SVGClipPathElement>, 
    IAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IShapeElementBuilder
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGClipPathElementBuilder](svgclippathelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgclippathelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | clipPath 要素に script 要素を追加します。 |
| [AddText](../../aspose.svg.builder/svgclippathelementbuilder/addtext/)(*Action&lt;SVGTextElementBuilder&gt;*) | clipPath 要素に text 要素を追加します。 |
| [AddUse](../../aspose.svg.builder/svgclippathelementbuilder/adduse/)(*Action&lt;SVGUseElementBuilder&gt;*) | clipPath 要素に 'use' 要素を追加します。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGClipPathElement](../../aspose.svg/svgclippathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [ClipPathUnits](../../aspose.svg.builder/svgclippathelementbuilder/clippathunits/)(*[CoordinateUnits](../coordinateunits/)*) | SVG の 'clipPath' 要素の 'clipPathUnits' 属性を設定し、クリッピング パスの座標系を指定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGClipPathElement](../../aspose.svg/svgclippathelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IShapeElementBuilder](../ishapeelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
