---
title: "Classe SVGFEComponentTransferElementBuilder"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Builder.SVGFEComponentTransferElementBuilder. Classe builder per creare elementi SVG feComponentTransfer utilizzati nei filtri SVG"
type: docs
weight: 1210
url: /it/net/aspose.svg.builder/svgfecomponenttransferelementbuilder/
---
## SVGFEComponentTransferElementBuilder class

Classe Builder per la creazione di elementi SVG 'feComponentTransfer', utilizzati nei filtri SVG.

```csharp
public class SVGFEComponentTransferElementBuilder : 
    SVGElementBuilder<SVGFEComponentTransferElement>, ICoreAttributeSetter, 
    IDescriptiveElementBuilder, IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGFEComponentTransferElementBuilder](svgfecomponenttransferelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Crea l'SVGFEComponentTransferElement con le funzioni di trasferimento componenti configurate. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEComponentTransferElement](../../aspose.svg.filters/svgfecomponenttransferelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [WithFeFuncA](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/withfefunca/)(*Action&lt;SVGFEFuncAElementBuilder&gt;*) | Configura la funzione di trasferimento componenti 'feFuncA' per il canale alfa. |
| [WithFeFuncB](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/withfefuncb/)(*Action&lt;SVGFEFuncBElementBuilder&gt;*) | Configura la funzione di trasferimento componenti 'feFuncB' per il canale blu. |
| [WithFeFuncG](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/withfefuncg/)(*Action&lt;SVGFEFuncGElementBuilder&gt;*) | Configura la funzione di trasferimento componenti 'feFuncG' per il canale verde. |
| [WithFeFuncR](../../aspose.svg.builder/svgfecomponenttransferelementbuilder/withfefuncr/)(*Action&lt;SVGFEFuncRElementBuilder&gt;*) | Configura la funzione di trasferimento componenti 'feFuncR' per il canale rosso. |

### Vedi anche

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEComponentTransferElement](../../aspose.svg.filters/svgfecomponenttransferelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
