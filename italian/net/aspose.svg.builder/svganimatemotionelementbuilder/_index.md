---
title: "Classe SVGAnimateMotionElementBuilder"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Builder.SVGAnimateMotionElementBuilder. Classe builder per costruire un elemento SVG animateMotion che è usato per creare animazioni di movimento all'interno della grafica SVG. Consente la costruzione del contenuto all'interno dell'elemento animateMotion e fornisce metodi per impostare vari attributi specifici dell'elemento animateMotion in SVG"
type: docs
weight: 1090
url: /it/net/aspose.svg.builder/svganimatemotionelementbuilder/
---
## SVGAnimateMotionElementBuilder class

Classe builder per la costruzione di un elemento SVG 'animateMotion', utilizzato per creare animazioni di movimento all'interno di grafica SVG. Consente la creazione di contenuti all'interno dell'elemento 'animateMotion' e fornisce metodi per impostare vari attributi specifici dell'elemento 'animateMotion' in SVG.

```csharp
public class SVGAnimateMotionElementBuilder : SVGElementBuilder<SVGAnimateMotionElement>, 
    IAnimationAdditionAttributeSetter, IAnimationEventAttributeSetter, 
    IAnimationTargetElementAttributeSetter, IAnimationTimingAttributeSetter, 
    IAnimationValueAttributeSetter, IConditionalProcessingAttributeSetter, ICoreAttributeSetter, 
    IDescriptiveElementBuilder, IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IXLinkAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGAnimateMotionElementBuilder](svganimatemotionelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGAnimateMotionElement](../../aspose.svg/svganimatemotionelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [KeyPoints](../../aspose.svg.builder/svganimatemotionelementbuilder/keypoints/)(*params double[]*) | Imposta l'attributo 'keyPoints', definendo i punti in cui avviene l'animazione. |
| [Path](../../aspose.svg.builder/svganimatemotionelementbuilder/path/)(*Action&lt;PathBuilder&gt;*) | Definisce il percorso per l'animazione di movimento. |
| [Rotate](../../aspose.svg.builder/svganimatemotionelementbuilder/rotate/#rotate_1)(*double*) | Imposta l'attributo 'rotate', definendo la rotazione dell'elemento animato. |
| [Rotate](../../aspose.svg.builder/svganimatemotionelementbuilder/rotate/#rotate)(*[Rotate](../rotate/)*) | Imposta l'attributo 'rotate' usando un valore di rotazione predefinito. |

### Vedi anche

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
