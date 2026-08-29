---
title: "SVGSetElementBuilder Class"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Builder.SVGSetElementBuilder class. Builder‑klasse voor het construeren van een SVG‑set‑element. Het set‑element wordt gebruikt om een eenvoudige animatie te definiëren waarbij een enkele attribuutwaarde gedurende een tijdsperiode verandert. Deze klasse biedt methoden om verschillende attributen specifiek voor het set‑element in te stellen, zoals het doelattribuut en de in te stellen waarde."
type: docs
weight: 1610
url: /nl/net/aspose.svg.builder/svgsetelementbuilder/
---
## SVGSetElementBuilder class

Builder-klasse voor het construeren van een SVG 'set'-element. Het 'set'-element wordt gebruikt om een eenvoudige animatie te definiëren waarbij een enkele attribuutwaarde gedurende een periode verandert. Deze klasse biedt methoden om verschillende attributen specifiek voor het 'set'-element in te stellen, zoals het doelattribuut en de in te stellen waarde.

```csharp
public class SVGSetElementBuilder : SVGElementBuilder<SVGSetElement>, 
    IAnimationEventAttributeSetter, IAnimationTargetAttributeSetter, 
    IAnimationTargetElementAttributeSetter, IAnimationTimingAttributeSetter, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SVGSetElementBuilder](svgsetelementbuilder/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGSetElement](../../aspose.svg/svgsetelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [To](../../aspose.svg.builder/svgsetelementbuilder/to/)(*string*) | Stelt het 'to'-attribuut van het SVG 'set'-element in, waarmee de uiteindelijke waarde van het attribuut wordt gespecificeerd die tijdens de animatie zal worden gewijzigd. |

### Zie ook

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
