---
title: "SVGFEColorMatrixElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGFEColorMatrixElementBuilder クラス。SVG フィルターで使用される SVG feColorMatrix 要素を作成するためのビルダー クラスです。"
type: docs
weight: 1200
url: /ja/net/aspose.svg.builder/svgfecolormatrixelementbuilder/
---
## SVGFEColorMatrixElementBuilder class

SVG の 'feColorMatrix' 要素を作成するための Builder クラスで、SVG フィルターで使用されます。

```csharp
public class SVGFEColorMatrixElementBuilder : SVGElementBuilder<SVGFEColorMatrixElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGFEColorMatrixElementBuilder](svgfecolormatrixelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfecolormatrixelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | feColorMatrix 要素にスクリプト構成を追加します。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEColorMatrixElement](../../aspose.svg.filters/svgfecolormatrixelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [TypeAndValues](../../aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/)(*[ColorMatrixOperation](../colormatrixoperation/), params double[]*) | feColorMatrix 要素の 'type' と 'values' 属性を設定し、カラー行列の操作とそのパラメータを指定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEColorMatrixElement](../../aspose.svg.filters/svgfecolormatrixelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
