---
title: "SVGAnimateMotionElementBuilder-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.SVGAnimateMotionElementBuilder-klass. Byggklass för att konstruera ett SVG animateMotion-element som används för att skapa rörelsesanimationer inom SVG-grafik. Den möjliggör byggandet av innehåll inom animateMotion-elementet och tillhandahåller metoder för att ställa in olika attribut som är specifika för animateMotion-elementet i SVG."
type: docs
weight: 1090
url: /sv/net/aspose.svg.builder/svganimatemotionelementbuilder/
---
## SVGAnimateMotionElementBuilder class

Builder‑klass för att konstruera ett SVG‑element 'animateMotion', som används för att skapa rörelsanimationer i SVG‑grafik. Den möjliggör byggandet av innehåll inom 'animateMotion'-elementet och tillhandahåller metoder för att ange olika attribut som är specifika för 'animateMotion'-elementet i SVG.

```csharp
public class SVGAnimateMotionElementBuilder : SVGElementBuilder<SVGAnimateMotionElement>, 
    IAnimationAdditionAttributeSetter, IAnimationEventAttributeSetter, 
    IAnimationTargetElementAttributeSetter, IAnimationTimingAttributeSetter, 
    IAnimationValueAttributeSetter, IConditionalProcessingAttributeSetter, ICoreAttributeSetter, 
    IDescriptiveElementBuilder, IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IXLinkAttributeSetter
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SVGAnimateMotionElementBuilder](svganimatemotionelementbuilder/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGAnimateMotionElement](../../aspose.svg/svganimatemotionelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [KeyPoints](../../aspose.svg.builder/svganimatemotionelementbuilder/keypoints/)(*params double[]*) | Ställer in attributet 'keyPoints', vilket definierar de punkter där animationen sker. |
| [Path](../../aspose.svg.builder/svganimatemotionelementbuilder/path/)(*Action&lt;PathBuilder&gt;*) | Definierar sökvägen för rörelsesanimationen. |
| [Rotate](../../aspose.svg.builder/svganimatemotionelementbuilder/rotate/#rotate_1)(*double*) | Ställer in attributet 'rotate', vilket definierar rotationen av det animerade elementet. |
| [Rotate](../../aspose.svg.builder/svganimatemotionelementbuilder/rotate/#rotate)(*[Rotate](../rotate/)*) | Ställer in attributet 'rotate' med ett fördefinierat rotationsvärde. |

### Se även

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGAnimateMotionElement](../../aspose.svg/svganimatemotionelement/)
* interface [IAnimationAdditionAttributeSetter](../ianimationadditionattributesetter/)
* interface [IAnimationEventAttributeSetter](../ianimationeventattributesetter/)
* interface [IAnimationTargetElementAttributeSetter](../ianimationtargetelementattributesetter/)
* interface [IAnimationTimingAttributeSetter](../ianimationtimingattributesetter/)
* interface [IAnimationValueAttributeSetter](../ianimationvalueattributesetter/)
* interface [IConditionalProcessingAttributeSetter](../iconditionalprocessingattributesetter/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IXLinkAttributeSetter](../ixlinkattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
