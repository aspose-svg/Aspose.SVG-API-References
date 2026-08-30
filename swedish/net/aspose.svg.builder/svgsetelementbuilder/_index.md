---
title: "SVGSetElementBuilder-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.SVGSetElementBuilder-klass. Byggklass för att konstruera ett SVG set-element. Set-elementet används för att definiera en enkel animation där ett enda attributvärde förändras över en tidsperiod. Denna klass tillhandahåller metoder för att ange olika attribut specifika för set-elementet, såsom målattributet och värdet som ska sättas."
type: docs
weight: 1610
url: /sv/net/aspose.svg.builder/svgsetelementbuilder/
---
## SVGSetElementBuilder class

Builder-klass för att konstruera ett SVG 'set'-element. 'Set'-elementet används för att definiera en enkel animation där ett enskilt attributvärde förändras över en tidsperiod. Denna klass tillhandahåller metoder för att ange olika attribut som är specifika för 'set'-elementet, såsom målattributet och värdet som ska sättas.

```csharp
public class SVGSetElementBuilder : SVGElementBuilder<SVGSetElement>, 
    IAnimationEventAttributeSetter, IAnimationTargetAttributeSetter, 
    IAnimationTargetElementAttributeSetter, IAnimationTimingAttributeSetter, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SVGSetElementBuilder](svgsetelementbuilder/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGSetElement](../../aspose.svg/svgsetelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [To](../../aspose.svg.builder/svgsetelementbuilder/to/)(*string*) | Anger 'to'-attributet för SVG 'set'-elementet och specificerar det slutgiltiga värdet på attributet som kommer att förändras under animationen. |

### Se även

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGSetElement](../../aspose.svg/svgsetelement/)
* interface [IAnimationEventAttributeSetter](../ianimationeventattributesetter/)
* interface [IAnimationTargetAttributeSetter](../ianimationtargetattributesetter/)
* interface [IAnimationTargetElementAttributeSetter](../ianimationtargetelementattributesetter/)
* interface [IAnimationTimingAttributeSetter](../ianimationtimingattributesetter/)
* interface [IConditionalProcessingAttributeSetter](../iconditionalprocessingattributesetter/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
