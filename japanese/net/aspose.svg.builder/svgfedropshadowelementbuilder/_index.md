---
title: "SVGFEDropShadowElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGFEDropShadowElementBuilder クラス。SVG フィルター内で使用され、ドロップシャドウ効果を適用する SVG feDropShadow 要素を作成するビルダー クラスです。"
type: docs
weight: 1270
url: /ja/net/aspose.svg.builder/svgfedropshadowelementbuilder/
---
## SVGFEDropShadowElementBuilder class

SVG の 'feDropShadow' 要素を作成するための Builder クラスで、ドロップシャドウ効果を適用するために SVG フィルター内で使用されます。

```csharp
public class SVGFEDropShadowElementBuilder : SVGElementBuilder<SVGFEDropShadowElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGFEDropShadowElementBuilder](svgfedropshadowelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfedropshadowelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | feDropShadow 要素にスクリプト構成を追加します。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEDropShadowElement](../../aspose.svg.filters/svgfedropshadowelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Dx](../../aspose.svg.builder/svgfedropshadowelementbuilder/dx/)(*double*) | ドロップシャドウの水平オフセット（'dx'）を設定します。 |
| [Dy](../../aspose.svg.builder/svgfedropshadowelementbuilder/dy/)(*double*) | ドロップシャドウの垂直オフセット（'dy'）を設定します。 |
| [StdDeviation](../../aspose.svg.builder/svgfedropshadowelementbuilder/stddeviation/)(*double, double?*) | ドロップシャドウのぼかし効果の標準偏差を設定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEDropShadowElement](../../aspose.svg.filters/svgfedropshadowelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
