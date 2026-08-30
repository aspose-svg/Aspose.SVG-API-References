---
title: "SVGTextPathElementBuilder-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.SVGTextPathElementBuilder-klass. Byggarklass för att skapa SVG textPath-element som används för att justera text till en bana."
type: docs
weight: 1680
url: /sv/net/aspose.svg.builder/svgtextpathelementbuilder/
---
## SVGTextPathElementBuilder class

Builder-klass för att skapa SVG 'textPath'-element, som används för att justera text till en bana.

```csharp
public class SVGTextPathElementBuilder : SVGElementBuilder<SVGTextPathElement>, 
    IBaseAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IPaintServerElementBuilder, IShapeContentElementBuilder, ITextContentSetter
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SVGTextPathElementBuilder](svgtextpathelementbuilder/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddA](../../aspose.svg.builder/svgtextpathelementbuilder/adda/)(*Action&lt;SVGAElementBuilder&gt;*) | Lägger till en 'a' (ankare) elementkonfiguration till 'textPath'. |
| [AddTSpan](../../aspose.svg.builder/svgtextpathelementbuilder/addtspan/)(*Action&lt;SVGTSpanElementBuilder&gt;*) | Lägger till en 'tspan' elementkonfiguration till 'textPath'. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGTextPathElement](../../aspose.svg/svgtextpathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgtextpathelementbuilder/href/)(*string*) | Ställer in attributet 'href', vilket specificerar en referens till ett path-element. |
| [LengthAdjust](../../aspose.svg.builder/svgtextpathelementbuilder/lengthadjust/)(*[LengthAdjust](../lengthadjust/)*) | Ställer in attributet 'lengthAdjust', vilket specificerar hur textlängdsjusteringar görs. |
| [Method](../../aspose.svg.builder/svgtextpathelementbuilder/method/)(*[TextPathMethod](../textpathmethod/)*) | Ställer in attributet 'method', vilket specificerar textlayoutmetoden längs vägen. |
| [Path](../../aspose.svg.builder/svgtextpathelementbuilder/path/)(*Action&lt;PathBuilder&gt;*) | Konfigurerar sökvägen för texten. |
| [Side](../../aspose.svg.builder/svgtextpathelementbuilder/side/)(*[HorizontalEdge](../horizontaledge/)*) | Ställer in attributet 'side' och specificerar på vilken sida av sökvägen texten placeras. |
| [Spacing](../../aspose.svg.builder/svgtextpathelementbuilder/spacing/)(*[TextPathSpacing](../textpathspacing/)*) | Ställer in attributet 'spacing' och specificerar avståndsstrategin för text längs sökvägen. |
| [StartOffset](../../aspose.svg.builder/svgtextpathelementbuilder/startoffset/)(*double, [LengthType](../lengthtype/)*) | Ställer in attributet 'startOffset' och specificerar startpositionen för texten på sökvägen. |
| [TextLength](../../aspose.svg.builder/svgtextpathelementbuilder/textlength/)(*double, [LengthType](../lengthtype/)*) | Ställer in attributet 'textLength' och specificerar textens längd. |

### Se även

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGTextPathElement](../../aspose.svg/svgtextpathelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* interface [ITextContentSetter](../itextcontentsetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
