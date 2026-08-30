---
title: "SVGPatternElementBuilder Class"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.SVGPatternElementBuilder class. Builder-klass för att konstruera ett SVG-mönsterelement som används för att definiera ett mönster som ska användas för att fylla grafikelement inom SVG. Denna klass tillhandahåller metoder för att sätta olika attribut specifika för mönsterelementet och för att bygga dess innehåll."
type: docs
weight: 1540
url: /sv/net/aspose.svg.builder/svgpatternelementbuilder/
---
## SVGPatternElementBuilder class

Builder-klass för att konstruera ett SVG 'pattern'-element, som används för att definiera ett mönster som ska användas för att fylla grafikelement inom SVG. Denna klass tillhandahåller metoder för att ange olika attribut som är specifika för 'pattern'-elementet och för att bygga dess innehåll.

```csharp
public class SVGPatternElementBuilder : SVGElementBuilder<SVGPatternElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, IRectAttributeSetter, 
    IViewBoxAttributeSetter
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SVGPatternElementBuilder](svgpatternelementbuilder/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGPatternElement](../../aspose.svg/svgpatternelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgpatternelementbuilder/href/)(*string*) | Sätter attributet 'href' för SVG 'pattern'-elementet och anger en referens till ett annat mönster som detta mönster ärver attribut från. |
| [PatternContentUnits](../../aspose.svg.builder/svgpatternelementbuilder/patterncontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | Sätter attributet 'patternContentUnits' för SVG 'pattern'-elementet och anger koordinatsystemet för mönstrets innehåll. |
| [PatternTransform](../../aspose.svg.builder/svgpatternelementbuilder/patterntransform/)(*Func&lt;TransformBuilder, TransformBuilder&gt;*) | Sätter attributet 'patternTransform' för SVG 'pattern'-elementet och tillämpar en transformation på mönstret. |
| [PatternUnits](../../aspose.svg.builder/svgpatternelementbuilder/patternunits/)(*[CoordinateUnits](../coordinateunits/)*) | Sätter attributet 'patternUnits' för SVG 'pattern'-elementet och anger koordinatsystemet för mönstrets x, y, bredd och höjd. |

### Se även

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGPatternElement](../../aspose.svg/svgpatternelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
