---
title: "SVGFilterElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGFilterElementBuilder クラス。SVG グラフィックに適用できるフィルター効果を定義する SVG フィルター要素を作成するためのビルダー クラスです。"
type: docs
weight: 1440
url: /ja/net/aspose.svg.builder/svgfilterelementbuilder/
---
## SVGFilterElementBuilder class

SVG の 'filter' 要素を作成するためのビルダー クラスで、SVG グラフィックに適用できるフィルター効果を定義します。

```csharp
public class SVGFilterElementBuilder : SVGElementBuilder<SVGFilterElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IFilterPrimitiveElementBuilder, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter, IRectAttributeSetter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGFilterElementBuilder](svgfilterelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfilterelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | フィルター要素にスクリプト構成を追加します。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFilterElement](../../aspose.svg/svgfilterelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [FilterUnits](../../aspose.svg.builder/svgfilterelementbuilder/filterunits/)(*[CoordinateUnits](../coordinateunits/)*) | フィルターの x、y、幅、高さ属性の座標系を設定します。 |
| [PrimitiveUnits](../../aspose.svg.builder/svgfilterelementbuilder/primitiveunits/)(*[CoordinateUnits](../coordinateunits/)*) | フィルターのプリミティブサブ要素の座標系を設定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFilterElement](../../aspose.svg/svgfilterelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IFilterPrimitiveElementBuilder](../ifilterprimitiveelementbuilder/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
