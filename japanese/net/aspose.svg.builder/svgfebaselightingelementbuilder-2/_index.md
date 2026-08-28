---
title: "SVGFEBaseLightingElementBuilderTElementTBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGFEBaseLightingElementBuilder2TElementTBuilder クラス。SVG フィルター効果の照明要素ビルダーの抽象基底クラス"
type: docs
weight: 1180
url: /ja/net/aspose.svg.builder/svgfebaselightingelementbuilder-2/
---
## SVGFEBaseLightingElementBuilder<TElement,TBuilder> class

SVG フィルタ効果の照明要素のビルダー用抽象基底クラスです。

```csharp
public abstract class SVGFEBaseLightingElementBuilder<TElement, TBuilder> : 
    SVGElementBuilder<TElement>, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
    where TElement : SVGElement
    where TBuilder : SVGFEBaseLightingElementBuilder
```

| パラメータ | 説明 |
| --- | --- |
| TElement | 構築中の SVG 要素の型です。 |
| TBuilder | ビルダー自体の型です。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | 要素にスクリプト構成を追加します。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | 指定されている場合、光源構成を適用しながら SVG 要素を構築します。 |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*TElement*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [WithFeDistantLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfedistantlight/)(*Action&lt;SVGFEDistantLightElementBuilder&gt;*) | フィルター効果のために遠距離光源を設定します。 |
| [WithFePointLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfepointlight/)(*Action&lt;SVGFEPointLightElementBuilder&gt;*) | フィルター効果のためにポイント光源を設定します。 |
| [WithFeSpotLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfespotlight/)(*Action&lt;SVGFESpotLightElementBuilder&gt;*) | フィルター効果のためにスポット光源を設定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
