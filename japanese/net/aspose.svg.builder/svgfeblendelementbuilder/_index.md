---
title: "SVGFEBlendElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGFEBlendElementBuilder クラス。SVG フィルターで使用される SVG feBlend 要素を作成するためのビルダー クラス"
type: docs
weight: 1190
url: /ja/net/aspose.svg.builder/svgfeblendelementbuilder/
---
## SVGFEBlendElementBuilder class

SVG の 'feBlend' 要素を作成するための Builder クラスで、SVG フィルターで使用されます。

```csharp
public class SVGFEBlendElementBuilder : SVGElementBuilder<SVGFEBlendElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGFEBlendElementBuilder](svgfeblendelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfeblendelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | feBlend 要素にスクリプト構成を追加します。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEBlendElement](../../aspose.svg.filters/svgfeblendelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [In2](../../aspose.svg.builder/svgfeblendelementbuilder/in2/#in2)(*[FilterInput](../filterinput/)*) | feBlend 要素の 'in2' 属性を設定し、ブレンド操作の第2入力を指定します。 |
| [In2](../../aspose.svg.builder/svgfeblendelementbuilder/in2/#in2_1)(*string*) | feBlend 要素の 'in2' 属性を設定し、ブレンド操作の第2入力を指定します。 |
| [Mode](../../aspose.svg.builder/svgfeblendelementbuilder/mode/)(*[BlendMode](../blendmode/)*) | feBlend 要素の 'mode' 属性を設定し、使用するブレンドモードを指定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEBlendElement](../../aspose.svg.filters/svgfeblendelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
