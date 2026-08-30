---
title: "SVGTextElementBuilder Klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.SVGTextElementBuilder klass. Builder-klass för att skapa ett SVGTextElement som används för att definiera text i ett SVG-dokument"
type: docs
weight: 1670
url: /sv/net/aspose.svg.builder/svgtextelementbuilder/
---
## SVGTextElementBuilder class

Builder-klass för att skapa ett SVGTextElement, som används för att definiera text i ett SVG-dokument.

```csharp
public class SVGTextElementBuilder : SVGElementBuilder<SVGTextElement>, IAnimationElementBuilder, 
    ICompositeAttributeSetter, IDescriptiveElementBuilder, IPaintServerElementBuilder, 
    IShapeContentElementBuilder, ITextContentPositioningAttributeSetter
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SVGTextElementBuilder](svgtextelementbuilder/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddA](../../aspose.svg.builder/svgtextelementbuilder/adda/)(*Action&lt;SVGAElementBuilder&gt;*) | Lägger till ett 'a' (ankare) element till textelementet, vilket möjliggör hyperlänkning av delar av texten. |
| [AddTextPath](../../aspose.svg.builder/svgtextelementbuilder/addtextpath/)(*Action&lt;SVGTextPathElementBuilder&gt;*) | Lägger till ett 'textPath'-element till textelementet, vilket gör att texten kan följa en definierad bana. |
| [AddTSpan](../../aspose.svg.builder/svgtextelementbuilder/addtspan/)(*Action&lt;SVGTSpanElementBuilder&gt;*) | Lägger till ett 'tspan'-element till textelementet, vilket ger fin kontroll över enskilda sektioner av texten. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGTextElement](../../aspose.svg/svgtextelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |

### Se även

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGTextElement](../../aspose.svg/svgtextelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../itextcontentpositioningattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
