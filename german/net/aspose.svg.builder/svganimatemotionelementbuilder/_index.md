---
title: "SVGAnimateMotionElementBuilder Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.SVGAnimateMotionElementBuilder Klasse. Builder‑Klasse zum Erstellen eines SVG‑animateMotion‑Elements, das für die Erstellung von Bewegungsanimationen innerhalb von SVG‑Grafiken verwendet wird. Sie ermöglicht das Erstellen von Inhalt innerhalb des animateMotion‑Elements und bietet Methoden zum Festlegen verschiedener Attribute, die speziell für das animateMotion‑Element in SVG gelten."
type: docs
weight: 1090
url: /de/net/aspose.svg.builder/svganimatemotionelementbuilder/
---
## SVGAnimateMotionElementBuilder class

Builder-Klasse zum Erstellen eines SVG-'animateMotion'-Elements, das zum Erzeugen von Bewegungsanimationen innerhalb von SVG-Grafiken verwendet wird. Sie ermöglicht das Erstellen von Inhalt innerhalb des 'animateMotion'-Elements und stellt Methoden zum Festlegen verschiedener, für das 'animateMotion'-Element in SVG spezifischer Attribute bereit.

```csharp
public class SVGAnimateMotionElementBuilder : SVGElementBuilder<SVGAnimateMotionElement>, 
    IAnimationAdditionAttributeSetter, IAnimationEventAttributeSetter, 
    IAnimationTargetElementAttributeSetter, IAnimationTimingAttributeSetter, 
    IAnimationValueAttributeSetter, IConditionalProcessingAttributeSetter, ICoreAttributeSetter, 
    IDescriptiveElementBuilder, IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IXLinkAttributeSetter
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SVGAnimateMotionElementBuilder](svganimatemotionelementbuilder/)() | Der Standard‑Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGAnimateMotionElement](../../aspose.svg/svganimatemotionelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [KeyPoints](../../aspose.svg.builder/svganimatemotionelementbuilder/keypoints/)(*params double[]*) | Setzt das Attribut 'keyPoints' und definiert die Punkte, an denen die Animation stattfindet. |
| [Path](../../aspose.svg.builder/svganimatemotionelementbuilder/path/)(*Action&lt;PathBuilder&gt;*) | Definiert den Pfad für die Bewegungsanimation. |
| [Rotate](../../aspose.svg.builder/svganimatemotionelementbuilder/rotate/#rotate_1)(*double*) | Setzt das Attribut 'rotate' und definiert die Drehung des animierten Elements. |
| [Rotate](../../aspose.svg.builder/svganimatemotionelementbuilder/rotate/#rotate)(*[Rotate](../rotate/)*) | Setzt das Attribut 'rotate' unter Verwendung eines vordefinierten Drehwerts. |

### Siehe auch

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
