---
title: "SVGAnimateMotionElementBuilder Class"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Builder.SVGAnimateMotionElementBuilder class. Builderklasse voor het construeren van een SVG animateMotion-element dat wordt gebruikt voor het maken van bewegingsanimaties binnen SVG-afbeeldingen. Het maakt het bouwen van inhoud binnen het animateMotion-element mogelijk en biedt methoden om verschillende attributen in te stellen die specifiek zijn voor het animateMotion-element in SVG"
type: docs
weight: 1090
url: /nl/net/aspose.svg.builder/svganimatemotionelementbuilder/
---
## SVGAnimateMotionElementBuilder class

Builderklasse voor het construeren van een SVG 'animateMotion'-element, dat wordt gebruikt voor het maken van bewegingsanimaties binnen SVG‑graphics. Het maakt het bouwen van inhoud binnen het 'animateMotion'-element mogelijk en biedt methoden om verschillende attributen die specifiek zijn voor het 'animateMotion'-element in SVG in te stellen.

```csharp
public class SVGAnimateMotionElementBuilder : SVGElementBuilder<SVGAnimateMotionElement>, 
    IAnimationAdditionAttributeSetter, IAnimationEventAttributeSetter, 
    IAnimationTargetElementAttributeSetter, IAnimationTimingAttributeSetter, 
    IAnimationValueAttributeSetter, IConditionalProcessingAttributeSetter, ICoreAttributeSetter, 
    IDescriptiveElementBuilder, IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IXLinkAttributeSetter
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SVGAnimateMotionElementBuilder](svganimatemotionelementbuilder/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGAnimateMotionElement](../../aspose.svg/svganimatemotionelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [KeyPoints](../../aspose.svg.builder/svganimatemotionelementbuilder/keypoints/)(*params double[]*) | Stelt het 'keyPoints'-attribuut in, waarbij de punten worden gedefinieerd waarop de animatie plaatsvindt. |
| [Path](../../aspose.svg.builder/svganimatemotionelementbuilder/path/)(*Action&lt;PathBuilder&gt;*) | Definieert het pad voor de bewegingsanimatie. |
| [Rotate](../../aspose.svg.builder/svganimatemotionelementbuilder/rotate/#rotate_1)(*double*) | Stelt het 'rotate'-attribuut in, waarbij de rotatie van het geanimeerde element wordt gedefinieerd. |
| [Rotate](../../aspose.svg.builder/svganimatemotionelementbuilder/rotate/#rotate)(*[Rotate](../rotate/)*) | Stelt het 'rotate'-attribuut in met behulp van een vooraf gedefinieerde rotatiewaarde. |

### Zie ook

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
