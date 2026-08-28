---
title: "Classe SVGFEImageElementBuilder"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Builder.SVGFEImageElementBuilder. Classe builder per creare elementi SVG feImage che definiscono un'immagine da utilizzare con altre primitive di filtro"
type: docs
weight: 1340
url: /it/net/aspose.svg.builder/svgfeimageelementbuilder/
---
## SVGFEImageElementBuilder class

Classe Builder per la creazione di elementi SVG 'feImage', che definiscono un'immagine da utilizzare da altre primitive di filtro.

```csharp
public class SVGFEImageElementBuilder : SVGElementBuilder<SVGFEImageElement>, 
    IAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveAttributeSetter, IPresentationAttributeSetter, 
    IPreserveAspectRatioAttributeSetter, IXLinkAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGFEImageElementBuilder](svgfeimageelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddAnimateTransform](../../aspose.svg.builder/svgfeimageelementbuilder/addanimatetransform/)(*Action&lt;SVGAnimateTransformElementBuilder&gt;*) | Aggiunge una configurazione di animazione di trasformazione all'elemento feImage. |
| [AddScript](../../aspose.svg.builder/svgfeimageelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Aggiunge una configurazione di script all'elemento feImage. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEImageElement](../../aspose.svg.filters/svgfeimageelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgfeimageelementbuilder/href/)(*string*) | Imposta l'attributo 'href' dell'elemento feImage, definendo l'URL dell'immagine da utilizzare. |

### Vedi anche

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEImageElement](../../aspose.svg.filters/svgfeimageelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveAttributeSetter](../ifilterprimitiveattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IXLinkAttributeSetter](../ixlinkattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
