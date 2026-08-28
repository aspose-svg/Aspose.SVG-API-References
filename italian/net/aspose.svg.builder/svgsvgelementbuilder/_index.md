---
title: "Classe SVGSVGElementBuilder"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Builder.SVGSVGElementBuilder. Classe builder per creare un SVGSVGElement, l'elemento radice di un documento SVG"
type: docs
weight: 1590
url: /it/net/aspose.svg.builder/svgsvgelementbuilder/
---
## SVGSVGElementBuilder class

Classe Builder per la creazione di un SVGSVGElement, l'elemento radice di un documento SVG.

```csharp
public class SVGSVGElementBuilder : SVGElementBuilder<SVGSVGElement>, ICompositeAttributeSetter, 
    ICompositeElementBuilder, IDocumentEventAttributeSetter, IPreserveAspectRatioAttributeSetter, 
    IRectAttributeSetter, IViewBoxAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGSVGElementBuilder](svgsvgelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| [BaseProfile](../../aspose.svg.builder/svgsvgelementbuilder/baseprofile/)(*double*) | Imposta l'attributo 'baseProfile' dell'elemento SVG. Questo attributo indica quale sottoinsieme della specifica SVG completa si applica al documento. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGSVGElement](../../aspose.svg/svgsvgelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [ContentScriptType](../../aspose.svg.builder/svgsvgelementbuilder/contentscripttype/)(*string*) | Imposta l'attributo 'contentScriptType' dell'elemento SVG. Questo attributo specifica il linguaggio di scripting predefinito per il contenuto del documento SVG. |
| [ContentStyleType](../../aspose.svg.builder/svgsvgelementbuilder/contentstyletype/)(*string*) | Imposta l'attributo 'contentStyleType' dell'elemento SVG. Questo attributo specifica il linguaggio di stile predefinito per il contenuto del documento SVG. |
| [Version](../../aspose.svg.builder/svgsvgelementbuilder/version/)(*double*) | Imposta l'attributo 'version' dell'elemento SVG. Questo attributo specifica la versione della specifica SVG a cui il documento si conforma. |
| [WithXlink](../../aspose.svg.builder/svgsvgelementbuilder/withxlink/)() | Aggiunge la dichiarazione dello spazio dei nomi XLink all'elemento SVG. Questo è necessario per utilizzare attributi XLink come 'xlink:href'. |
| [ZoomAndPan](../../aspose.svg.builder/svgsvgelementbuilder/zoomandpan/)(*string*) | Imposta l'attributo 'zoomAndPan' dell'elemento SVG. Questo attributo controlla se il contenuto SVG può essere ingrandito e spostato. |

### Vedi anche

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGSVGElement](../../aspose.svg/svgsvgelement/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [IDocumentEventAttributeSetter](../idocumenteventattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
