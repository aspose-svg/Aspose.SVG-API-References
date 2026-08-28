---
title: "SVGFEGaussianBlurElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGFEGaussianBlurElementBuilder クラス。ガウスぼかしフィルター効果を適用する SVG feGaussianBlur 要素を作成するためのビルダー クラスです"
type: docs
weight: 1330
url: /ja/net/aspose.svg.builder/svgfegaussianblurelementbuilder/
---
## SVGFEGaussianBlurElementBuilder class

SVG の 'feGaussianBlur' 要素を作成するための Builder クラスで、ガウスぼかしフィルター効果を適用します。

```csharp
public class SVGFEGaussianBlurElementBuilder : SVGElementBuilder<SVGFEGaussianBlurElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGFEGaussianBlurElementBuilder](svgfegaussianblurelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfegaussianblurelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | feGaussianBlur 要素にスクリプト構成を追加します。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEGaussianBlurElement](../../aspose.svg.filters/svgfegaussianblurelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [StdDeviation](../../aspose.svg.builder/svgfegaussianblurelementbuilder/stddeviation/)(*double, double?*) | ガウスぼかし効果の標準偏差を設定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEGaussianBlurElement](../../aspose.svg.filters/svgfegaussianblurelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
