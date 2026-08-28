---
title: "Classe SVGImageElementBuilder"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Builder.SVGImageElementBuilder. Classe builder per costruire un elemento immagine SVG. Questo elemento è usato per incorporare immagini all'interno di grafica SVG. Fornisce metodi per impostare vari attributi specifici dell'elemento immagine e per aggiungere configurazioni aggiuntive come percorsi di ritaglio, maschere, stili e script"
type: docs
weight: 1470
url: /it/net/aspose.svg.builder/svgimageelementbuilder/
---
## SVGImageElementBuilder class

Classe Builder per costruire un elemento SVG 'image'. Questo elemento è usato per incorporare immagini nella grafica SVG. Fornisce metodi per impostare vari attributi specifici dell'elemento 'image' e per aggiungere configurazioni aggiuntive come percorsi di ritaglio, maschere, stili e script.

```csharp
public class SVGImageElementBuilder : SVGElementBuilder<SVGImageElement>, IAnimationElementBuilder, 
    ICompositeAttributeSetter, IDescriptiveElementBuilder, IPreserveAspectRatioAttributeSetter, 
    IRectAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGImageElementBuilder](svgimageelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddClipPath](../../aspose.svg.builder/svgimageelementbuilder/addclippath/)(*Action&lt;SVGClipPathElementBuilder&gt;*) | Aggiunge una configurazione di percorso di ritaglio all'elemento SVG 'image'. |
| [AddMask](../../aspose.svg.builder/svgimageelementbuilder/addmask/)(*Action&lt;SVGMaskElementBuilder&gt;*) | Aggiunge una configurazione di maschera all'elemento SVG 'image'. |
| [AddScript](../../aspose.svg.builder/svgimageelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Aggiunge una configurazione di script all'elemento SVG 'image'. |
| [AddStyle](../../aspose.svg.builder/svgimageelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Aggiunge una configurazione di stile all'elemento SVG 'image'. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGImageElement](../../aspose.svg/svgimageelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgimageelementbuilder/href/)(*string*) | Imposta l'attributo 'href' dell'elemento SVG 'image', specificando l'URL dell'immagine da incorporare. |
| [HrefBase64FromBytes](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64frombytes/)(*byte[], string*) | Imposta l'attributo 'href' dell'elemento SVG 'image' utilizzando byte codificati in base64 di un'immagine. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile)(*string*) | Imposta l'attributo 'href' dell'elemento SVG 'image' utilizzando un file immagine codificato in base64. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile_1)(*string, string*) | Imposta l'attributo 'href' dell'elemento SVG 'image' utilizzando un file immagine codificato in base64 con un tipo MIME specificato. |

### Vedi anche

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGImageElement](../../aspose.svg/svgimageelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
