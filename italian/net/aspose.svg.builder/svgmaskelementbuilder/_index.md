---
title: "Classe SVGMaskElementBuilder"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Builder.SVGMaskElementBuilder. Classe builder per la costruzione di un elemento maschera SVG, utilizzato per definire una maschera alfa per comporre l'oggetto corrente nello sfondo. Questa classe consente la creazione di contenuti all'interno dell'elemento maschera e fornisce metodi per impostare vari attributi specifici dell'elemento maschera in SVG."
type: docs
weight: 1510
url: /it/net/aspose.svg.builder/svgmaskelementbuilder/
---
## SVGMaskElementBuilder class

Classe Builder per costruire un elemento SVG 'mask', che è usato per definire una maschera alfa per comporre l'oggetto corrente nello sfondo. Questa classe consente la costruzione del contenuto all'interno dell'elemento 'mask' e fornisce metodi per impostare vari attributi specifici dell'elemento 'mask' in SVG.

```csharp
public class SVGMaskElementBuilder : SVGElementBuilder<SVGMaskElement>, ICompositeElementBuilder, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IRectAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGMaskElementBuilder](svgmaskelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMaskElement](../../aspose.svg/svgmaskelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MaskContentUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskcontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | Imposta l'attributo 'maskContentUnits' dell'elemento SVG 'mask', specificando il sistema di coordinate per i contenuti della maschera. |
| [MaskUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskunits/)(*[CoordinateUnits](../coordinateunits/)*) | Imposta l'attributo 'maskUnits' dell'elemento SVG 'mask', specificando il sistema di coordinate per gli attributi della maschera. |

### Vedi anche

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
