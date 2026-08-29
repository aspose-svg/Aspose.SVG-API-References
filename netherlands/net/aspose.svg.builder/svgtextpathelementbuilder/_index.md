---
title: "SVGTextPathElementBuilder Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Builder.SVGTextPathElementBuilder klasse. Builderklasse voor het maken van SVG textPath‑elementen die worden gebruikt om tekst op een pad uit te lijnen."
type: docs
weight: 1680
url: /nl/net/aspose.svg.builder/svgtextpathelementbuilder/
---
## SVGTextPathElementBuilder class

Builder-klasse voor het maken van SVG 'textPath'-elementen, die worden gebruikt om tekst op een pad uit te lijnen.

```csharp
public class SVGTextPathElementBuilder : SVGElementBuilder<SVGTextPathElement>, 
    IBaseAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IPaintServerElementBuilder, IShapeContentElementBuilder, ITextContentSetter
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SVGTextPathElementBuilder](svgtextpathelementbuilder/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddA](../../aspose.svg.builder/svgtextpathelementbuilder/adda/)(*Action&lt;SVGAElementBuilder&gt;*) | Voegt een 'a' (anchor)‑elementconfiguratie toe aan de 'textPath'. |
| [AddTSpan](../../aspose.svg.builder/svgtextpathelementbuilder/addtspan/)(*Action&lt;SVGTSpanElementBuilder&gt;*) | Voegt een 'tspan'‑elementconfiguratie toe aan de 'textPath'. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGTextPathElement](../../aspose.svg/svgtextpathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgtextpathelementbuilder/href/)(*string*) | Stelt het 'href'‑attribuut in, waarmee een verwijzing naar een pad‑element wordt gespecificeerd. |
| [LengthAdjust](../../aspose.svg.builder/svgtextpathelementbuilder/lengthadjust/)(*[LengthAdjust](../lengthadjust/)*) | Stelt het 'lengthAdjust'‑attribuut in, waarmee wordt gespecificeerd hoe tekstlengte‑aanpassingen worden uitgevoerd. |
| [Method](../../aspose.svg.builder/svgtextpathelementbuilder/method/)(*[TextPathMethod](../textpathmethod/)*) | Stelt het 'method'‑attribuut in, waarmee de tekstindelingsmethode langs het pad wordt gespecificeerd. |
| [Path](../../aspose.svg.builder/svgtextpathelementbuilder/path/)(*Action&lt;PathBuilder&gt;*) | Configureert het pad voor de tekst. |
| [Side](../../aspose.svg.builder/svgtextpathelementbuilder/side/)(*[HorizontalEdge](../horizontaledge/)*) | Stelt het 'side'‑attribuut in, waarmee wordt gespecificeerd aan welke kant van het pad de tekst wordt geplaatst. |
| [Spacing](../../aspose.svg.builder/svgtextpathelementbuilder/spacing/)(*[TextPathSpacing](../textpathspacing/)*) | Stelt het 'spacing'‑attribuut in, waarmee de spatiëringsstrategie voor tekst langs het pad wordt gespecificeerd. |
| [StartOffset](../../aspose.svg.builder/svgtextpathelementbuilder/startoffset/)(*double, [LengthType](../lengthtype/)*) | Stelt het 'startOffset'‑attribuut in, waarmee de startpositie van de tekst op het pad wordt gespecificeerd. |
| [TextLength](../../aspose.svg.builder/svgtextpathelementbuilder/textlength/)(*double, [LengthType](../lengthtype/)*) | Stelt het 'textLength'‑attribuut in, waarmee de lengte van de tekst wordt gespecificeerd. |

### Zie ook

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
