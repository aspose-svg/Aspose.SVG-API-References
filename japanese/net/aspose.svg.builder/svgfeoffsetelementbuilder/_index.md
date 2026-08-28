---
title: "SVGFEOffsetElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGFEOffsetElementBuilder クラス。入力画像にオフセット効果を適用するために使用される SVG feOffset 要素を作成するビルダー クラスです。"
type: docs
weight: 1380
url: /ja/net/aspose.svg.builder/svgfeoffsetelementbuilder/
---
## SVGFEOffsetElementBuilder class

SVG の 'feOffset' 要素を作成するための Builder クラスで、入力画像にオフセット効果を適用するために使用されます。

```csharp
public class SVGFEOffsetElementBuilder : SVGElementBuilder<SVGFEOffsetElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGFEOffsetElementBuilder](svgfeoffsetelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfeoffsetelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | feOffset 要素にスクリプト構成を追加します。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEOffsetElement](../../aspose.svg.filters/svgfeoffsetelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Dx](../../aspose.svg.builder/svgfeoffsetelementbuilder/dx/)(*double*) | feOffset 要素の 'dx' 属性を設定し、水平オフセットを指定します。 |
| [Dy](../../aspose.svg.builder/svgfeoffsetelementbuilder/dy/)(*double*) | feOffset 要素の 'dy' 属性を設定し、垂直オフセットを指定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEOffsetElement](../../aspose.svg.filters/svgfeoffsetelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
