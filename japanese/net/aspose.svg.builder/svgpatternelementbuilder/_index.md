---
title: "SVGPatternElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGPatternElementBuilder クラス。SVG 内のグラフィック要素の塗りつぶしに使用されるパターンを定義するための SVG パターン要素を構築するビルダー クラスです。このクラスは、パターン要素固有のさまざまな属性を設定し、コンテンツを構築するためのメソッドを提供します"
type: docs
weight: 1540
url: /ja/net/aspose.svg.builder/svgpatternelementbuilder/
---
## SVGPatternElementBuilder class

SVG の 'pattern' 要素を構築するためのビルダー クラスで、SVG 内のグラフィック要素の塗りつぶしに使用されるパターンを定義するために使用されます。このクラスは 'pattern' 要素固有のさまざまな属性を設定するメソッドと、そのコンテンツを構築する機能を提供します。

```csharp
public class SVGPatternElementBuilder : SVGElementBuilder<SVGPatternElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, IRectAttributeSetter, 
    IViewBoxAttributeSetter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGPatternElementBuilder](svgpatternelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGPatternElement](../../aspose.svg/svgpatternelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgpatternelementbuilder/href/)(*string*) | SVG の 'pattern' 要素の 'href' 属性を設定し、このパターンが属性を継承する別のパターンへの参照を指定します。 |
| [PatternContentUnits](../../aspose.svg.builder/svgpatternelementbuilder/patterncontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | SVG の 'pattern' 要素の 'patternContentUnits' 属性を設定し、パターンの内容の座標系を指定します。 |
| [PatternTransform](../../aspose.svg.builder/svgpatternelementbuilder/patterntransform/)(*Func&lt;TransformBuilder, TransformBuilder&gt;*) | SVG の 'pattern' 要素の 'patternTransform' 属性を設定し、パターンに変換を適用します。 |
| [PatternUnits](../../aspose.svg.builder/svgpatternelementbuilder/patternunits/)(*[CoordinateUnits](../coordinateunits/)*) | SVG の 'pattern' 要素の 'patternUnits' 属性を設定し、パターンの x、y、幅、高さの座標系を指定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGPatternElement](../../aspose.svg/svgpatternelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
