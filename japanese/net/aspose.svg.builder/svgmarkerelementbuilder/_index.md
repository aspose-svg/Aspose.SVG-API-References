---
title: "SVGMarkerElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGMarkerElementBuilder クラス。パス、ライン、ポリライン、ポリゴン要素に付加できる矢じりや弾丸などのグラフィカルマーカーを定義するために使用される SVG マーカー要素を構築するビルダー クラスです。このクラスはマーカー要素内のコンテンツ構築を可能にし、SVG のマーカー要素固有のさまざまな属性を設定するメソッドを提供します。"
type: docs
weight: 1500
url: /ja/net/aspose.svg.builder/svgmarkerelementbuilder/
---
## SVGMarkerElementBuilder class

SVG の 'marker' 要素を構築するためのビルダー クラスで、'path'、'line'、'polyline'、'polygon' 要素に付加できる矢じりや点などのグラフィカルマーカーを定義するために使用されます。このクラスは 'marker' 要素内のコンテンツ構築を可能にし、SVG の 'marker' 要素固有のさまざまな属性を設定するメソッドを提供します。

```csharp
public class SVGMarkerElementBuilder : SVGElementBuilder<SVGMarkerElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, 
    IRefCoordinatesAttributeSetter, IViewBoxAttributeSetter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGMarkerElementBuilder](svgmarkerelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMarkerElement](../../aspose.svg/svgmarkerelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MarkerHeight](../../aspose.svg.builder/svgmarkerelementbuilder/markerheight/)(*double, [LengthType](../lengthtype/)*) | SVG の 'marker' 要素の 'markerHeight' 属性を設定し、マーカーのビューポートの高さを指定します。 |
| [MarkerUnits](../../aspose.svg.builder/svgmarkerelementbuilder/markerunits/)(*[MarkerUnits](../markerunits/)*) | SVG の 'marker' 要素の 'markerUnits' 属性を設定し、マーカー属性の座標系を指定します。 |
| [MarkerWidth](../../aspose.svg.builder/svgmarkerelementbuilder/markerwidth/)(*double, [LengthType](../lengthtype/)*) | SVG の 'marker' 要素の 'markerWidth' 属性を設定し、マーカーのビューポートの幅を指定します。 |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient)(*[Orient](../orient/)*) | SVG の 'marker' 要素の 'orient' 属性を設定し、マーカーの向きを指定します。 |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient_1)(*double, [AngleUnits](../angleunits/)*) | SVG の 'marker' 要素の 'orient' 属性を設定し、マーカーの向き角度を指定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGMarkerElement](../../aspose.svg/svgmarkerelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRefCoordinatesAttributeSetter](../irefcoordinatesattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
