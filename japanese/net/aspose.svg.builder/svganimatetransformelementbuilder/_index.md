---
title: "SVGAnimateTransformElementBuilder クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Builder.SVGAnimateTransformElementBuilder クラス。SVG グラフィック内で変換アニメーションを作成するために使用される SVG animateTransform 要素を構築するビルダー クラスです。animateTransform 要素内のコンテンツ構築を可能にし、SVG の animateTransform 要素固有のさまざまな属性を設定するメソッドを提供します。"
type: docs
weight: 1100
url: /ja/net/aspose.svg.builder/svganimatetransformelementbuilder/
---
## SVGAnimateTransformElementBuilder class

SVG グラフィック内で変換アニメーションを作成するために使用される SVG の 'animateTransform' 要素を構築するビルダー クラスです。'animateTransform' 要素内のコンテンツ構築を可能にし、SVG の 'animateTransform' 要素固有のさまざまな属性を設定するメソッドを提供します。

```csharp
public class SVGAnimateTransformElementBuilder : SVGElementBuilder<SVGAnimateTransformElement>, 
    IAnimationAdditionAttributeSetter, IAnimationEventAttributeSetter, 
    IAnimationTargetAttributeSetter, IAnimationTargetElementAttributeSetter, 
    IAnimationTimingAttributeSetter, IAnimationValueAttributeSetter, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGAnimateTransformElementBuilder](svganimatetransformelementbuilder/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGAnimateTransformElement](../../aspose.svg/svganimatetransformelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Type](../../aspose.svg.builder/svganimatetransformelementbuilder/type/)(*[TransformationType](../transformationtype/)*) | SVG の 'animateTransform' 要素の 'type' 属性を設定し、変換のタイプを指定します。 |

### 参照

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGAnimateTransformElement](../../aspose.svg/svganimatetransformelement/)
* interface [IAnimationAdditionAttributeSetter](../ianimationadditionattributesetter/)
* interface [IAnimationEventAttributeSetter](../ianimationeventattributesetter/)
* interface [IAnimationTargetAttributeSetter](../ianimationtargetattributesetter/)
* interface [IAnimationTargetElementAttributeSetter](../ianimationtargetelementattributesetter/)
* interface [IAnimationTimingAttributeSetter](../ianimationtimingattributesetter/)
* interface [IAnimationValueAttributeSetter](../ianimationvalueattributesetter/)
* interface [IConditionalProcessingAttributeSetter](../iconditionalprocessingattributesetter/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
