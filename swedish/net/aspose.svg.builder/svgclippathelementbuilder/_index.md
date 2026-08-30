---
title: "SVGClipPathElementBuilder klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.SVGClipPathElementBuilder-klass. Byggklass för att konstruera ett SVG clipPath-element som används för att definiera en beskärningsväg. Den möjliggör byggandet av innehåll inom clipPath-elementet och tillhandahåller metoder för att ställa in olika attribut som är specifika för clipPath-elementet i SVG"
type: docs
weight: 1130
url: /sv/net/aspose.svg.builder/svgclippathelementbuilder/
---
## SVGClipPathElementBuilder class

Byggarklass för att konstruera ett SVG 'clipPath'-element, som används för att definiera en beskärningsbana. Den möjliggör byggandet av innehåll inom 'clipPath'-elementet och tillhandahåller metoder för att ange olika attribut som är specifika för 'clipPath'-elementet i SVG.

```csharp
public class SVGClipPathElementBuilder : SVGElementBuilder<SVGClipPathElement>, 
    IAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IShapeElementBuilder
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SVGClipPathElementBuilder](svgclippathelementbuilder/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgclippathelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Lägger till ett script-element i clipPath-elementet. |
| [AddText](../../aspose.svg.builder/svgclippathelementbuilder/addtext/)(*Action&lt;SVGTextElementBuilder&gt;*) | Lägger till ett text-element i clipPath-elementet. |
| [AddUse](../../aspose.svg.builder/svgclippathelementbuilder/adduse/)(*Action&lt;SVGUseElementBuilder&gt;*) | Lägger till ett 'use'-element i clipPath-elementet. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGClipPathElement](../../aspose.svg/svgclippathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [ClipPathUnits](../../aspose.svg.builder/svgclippathelementbuilder/clippathunits/)(*[CoordinateUnits](../coordinateunits/)*) | Ställer in attributet 'clipPathUnits' för SVG 'clipPath'-elementet, vilket specificerar koordinatsystemet för beskärningsvägen. |

### Se även

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGClipPathElement](../../aspose.svg/svgclippathelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IShapeElementBuilder](../ishapeelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
