---
title: "Classe SVGTextElementBuilder"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Builder.SVGTextElementBuilder. Classe Builder per creare un SVGTextElement che viene usato per definire il testo in un documento SVG"
type: docs
weight: 1670
url: /it/net/aspose.svg.builder/svgtextelementbuilder/
---
## SVGTextElementBuilder class

Classe Builder per la creazione di un SVGTextElement, che è usato per definire testo in un documento SVG.

```csharp
public class SVGTextElementBuilder : SVGElementBuilder<SVGTextElement>, IAnimationElementBuilder, 
    ICompositeAttributeSetter, IDescriptiveElementBuilder, IPaintServerElementBuilder, 
    IShapeContentElementBuilder, ITextContentPositioningAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGTextElementBuilder](svgtextelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddA](../../aspose.svg.builder/svgtextelementbuilder/adda/)(*Action&lt;SVGAElementBuilder&gt;*) | Aggiunge un elemento 'a' (ancora) all'elemento di testo, consentendo l'ipertestualizzazione di parti del testo. |
| [AddTextPath](../../aspose.svg.builder/svgtextelementbuilder/addtextpath/)(*Action&lt;SVGTextPathElementBuilder&gt;*) | Aggiunge un elemento 'textPath' all'elemento di testo, consentendo al testo di seguire un percorso definito. |
| [AddTSpan](../../aspose.svg.builder/svgtextelementbuilder/addtspan/)(*Action&lt;SVGTSpanElementBuilder&gt;*) | Aggiunge un elemento 'tspan' all'elemento di testo, consentendo un controllo fine sulle singole sezioni del testo. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGTextElement](../../aspose.svg/svgtextelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |

### Vedi anche

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
