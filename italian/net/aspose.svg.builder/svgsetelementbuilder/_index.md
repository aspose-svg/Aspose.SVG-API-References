---
title: "Classe SVGSetElementBuilder"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Aspose.Svg.Builder.SVGSetElementBuilder classe. Classe builder per la costruzione di un elemento SVG set. L'elemento set è usato per definire un'animazione semplice in cui il valore di un singolo attributo cambia nel corso del tempo. Questa classe fornisce metodi per impostare vari attributi specifici dell'elemento set, come l'attributo target e il valore da impostare"
type: docs
weight: 1610
url: /it/net/aspose.svg.builder/svgsetelementbuilder/
---
## SVGSetElementBuilder class

Classe Builder per la costruzione di un elemento SVG 'set'. L'elemento 'set' è usato per definire un'animazione semplice in cui il valore di un singolo attributo cambia nel tempo. Questa classe fornisce metodi per impostare vari attributi specifici dell'elemento 'set', come l'attributo di destinazione e il valore da impostare.

```csharp
public class SVGSetElementBuilder : SVGElementBuilder<SVGSetElement>, 
    IAnimationEventAttributeSetter, IAnimationTargetAttributeSetter, 
    IAnimationTargetElementAttributeSetter, IAnimationTimingAttributeSetter, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGSetElementBuilder](svgsetelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGSetElement](../../aspose.svg/svgsetelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [To](../../aspose.svg.builder/svgsetelementbuilder/to/)(*string*) | Imposta l'attributo 'to' dell'elemento SVG 'set', specificando il valore finale dell'attributo che verrà modificato durante l'animazione. |

### Vedi anche

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
