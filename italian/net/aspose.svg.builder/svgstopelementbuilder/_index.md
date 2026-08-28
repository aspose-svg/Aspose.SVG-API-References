---
title: "Classe SVGStopElementBuilder"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Aspose.Svg.Builder.SVGStopElementBuilder class. Classe builder per la costruzione di un elemento stop SVG. L'elemento stop è utilizzato all'interno di una definizione di gradiente, sia lineare che radiale, per definire le fermate di colore. Questa classe fornisce metodi per impostare vari attributi specifici dell'elemento stop, come l'offset e il colore."
type: docs
weight: 1620
url: /it/net/aspose.svg.builder/svgstopelementbuilder/
---
## SVGStopElementBuilder class

Classe Builder per la costruzione di un elemento SVG 'stop'. L'elemento 'stop' è usato all'interno di una definizione di gradiente (lineare o radiale) per definire le fermate di colore. Questa classe fornisce metodi per impostare vari attributi specifici dell'elemento 'stop', come offset e colore.

```csharp
public class SVGStopElementBuilder : SVGElementBuilder<SVGStopElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGStopElementBuilder](svgstopelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgstopelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Aggiunge una configurazione di script all'elemento SVG 'stop'. |
| [AddStyle](../../aspose.svg.builder/svgstopelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Aggiunge una configurazione di stile all'elemento SVG 'stop'. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStopElement](../../aspose.svg/svgstopelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Offset](../../aspose.svg.builder/svgstopelementbuilder/offset/)(*double, [StopUnitType](../stopunittype/)*) | Imposta l'attributo 'offset' dell'elemento SVG 'stop', specificando la posizione della fermata di colore all'interno del gradiente. |

### Vedi anche

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStopElement](../../aspose.svg/svgstopelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
