---
title: "SVGRadialGradientElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGRadialGradientElementBuilder クラス。SVG の radialGradient 要素を構築するためのビルダー クラスで、SVG グラフィック内で放射状グラデーションを定義するために使用されます。このクラスは radialGradient 要素内のコンテンツ構築を可能にし、SVG の radialGradient 要素固有のさまざまな属性を設定するメソッドを提供します。"
type: docs
weight: 1570
url: /ja/net/aspose.svg.builder/svgradialgradientelementbuilder/
---
## SVGRadialGradientElementBuilder class

SVG の 'radialGradient' 要素を構築するためのビルダー クラスで、SVG グラフィック内の放射状グラデーションを定義するために使用されます。このクラスは 'radialGradient' 要素内のコンテンツ構築を可能にし、SVG の 'radialGradient' 要素固有のさまざまな属性を設定するメソッドを提供します。

```csharp
public class SVGRadialGradientElementBuilder : SVGElementBuilder<SVGRadialGradientElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, IGradientStopElementBuilder, 
    IPresentationAttributeSetter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGRadialGradientElementBuilder](svgradialgradientelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddAnimateTransform](../../aspose.svg.builder/svgradialgradientelementbuilder/addanimatetransform/)(*Action&lt;SVGAnimateTransformElementBuilder&gt;*) | SVG の 'radialGradient' 要素にアニメート変換構成を追加します。 |
| [AddScript](../../aspose.svg.builder/svgradialgradientelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | SVG の 'radialGradient' 要素にスクリプト構成を追加します。 |
| [AddStyle](../../aspose.svg.builder/svgradialgradientelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | SVG の 'radialGradient' 要素にスタイル構成を追加します。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGRadialGradientElement](../../aspose.svg/svgradialgradientelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Cx](../../aspose.svg.builder/svgradialgradientelementbuilder/cx/)(*double, [LengthType](../lengthtype/)*) | SVG の 'radialGradient' 要素の 'cx' 属性を設定し、グラデーションの中心の x 座標を指定します。 |
| [Cy](../../aspose.svg.builder/svgradialgradientelementbuilder/cy/)(*double, [LengthType](../lengthtype/)*) | SVG の 'radialGradient' 要素の 'cy' 属性を設定し、グラデーションの中心の y 座標を指定します。 |
| [Fx](../../aspose.svg.builder/svgradialgradientelementbuilder/fx/)(*double, [LengthType](../lengthtype/)*) | SVG の 'radialGradient' 要素の 'fx' 属性を設定し、グラデーションの焦点の x 座標を指定します。 |
| [Fy](../../aspose.svg.builder/svgradialgradientelementbuilder/fy/)(*double, [LengthType](../lengthtype/)*) | SVG の 'radialGradient' 要素の 'fy' 属性を設定し、グラデーションの焦点の y 座標を指定します。 |
| [Href](../../aspose.svg.builder/svgradialgradientelementbuilder/href/)(*string*) | SVG の 'radialGradient' 要素の 'href' 属性を設定し、別のグラデーションへの参照を指定します。 |
| [R](../../aspose.svg.builder/svgradialgradientelementbuilder/r/)(*double, [LengthType](../lengthtype/)*) | SVG の 'radialGradient' 要素の 'r' 属性を設定し、グラデーションの半径を指定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGRadialGradientElement](../../aspose.svg/svgradialgradientelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IGradientStopElementBuilder](../igradientstopelementbuilder/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
