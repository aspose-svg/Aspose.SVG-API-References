---
title: "SVGMaskElementBuilder-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.SVGMaskElementBuilder-klass. Byggklass för att konstruera ett SVG-maskelement som används för att definiera en alfamask för att komponera det aktuella objektet i bakgrunden. Denna klass möjliggör byggandet av innehåll inom maskelementet och tillhandahåller metoder för att sätta olika attribut som är specifika för maskelementet i SVG."
type: docs
weight: 1510
url: /sv/net/aspose.svg.builder/svgmaskelementbuilder/
---
## SVGMaskElementBuilder class

Builder-klass för att konstruera ett SVG 'mask'-element, som används för att definiera en alfamask för att komponera det aktuella objektet i bakgrunden. Denna klass möjliggör byggandet av innehåll inom 'mask'-elementet och tillhandahåller metoder för att ange olika attribut som är specifika för 'mask'-elementet i SVG.

```csharp
public class SVGMaskElementBuilder : SVGElementBuilder<SVGMaskElement>, ICompositeElementBuilder, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IRectAttributeSetter
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SVGMaskElementBuilder](svgmaskelementbuilder/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMaskElement](../../aspose.svg/svgmaskelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MaskContentUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskcontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | Sätter attributet 'maskContentUnits' för SVG 'mask'-elementet, vilket specificerar koordinatsystemet för maskens innehåll. |
| [MaskUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskunits/)(*[CoordinateUnits](../coordinateunits/)*) | Sätter attributet 'maskUnits' för SVG 'mask'-elementet, vilket specificerar koordinatsystemet för maskens attribut. |

### Se även

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGMaskElement](../../aspose.svg/svgmaskelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../iconditionalprocessingattributesetter/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
