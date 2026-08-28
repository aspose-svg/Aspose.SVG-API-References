---
title: "Classe SVGFEGaussianBlurElementBuilder"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Builder.SVGFEGaussianBlurElementBuilder. Classe builder per creare elementi SVG feGaussianBlur che applicano un effetto di filtro sfocatura gaussiana"
type: docs
weight: 1330
url: /it/net/aspose.svg.builder/svgfegaussianblurelementbuilder/
---
## SVGFEGaussianBlurElementBuilder class

Classe Builder per la creazione di elementi SVG 'feGaussianBlur', che applicano un effetto di sfocatura gaussiana.

```csharp
public class SVGFEGaussianBlurElementBuilder : SVGElementBuilder<SVGFEGaussianBlurElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGFEGaussianBlurElementBuilder](svgfegaussianblurelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfegaussianblurelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Aggiunge una configurazione di script all'elemento feGaussianBlur. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEGaussianBlurElement](../../aspose.svg.filters/svgfegaussianblurelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [StdDeviation](../../aspose.svg.builder/svgfegaussianblurelementbuilder/stddeviation/)(*double, double?*) | Imposta la deviazione standard per l'effetto di sfocatura gaussiana. |

### Vedi anche

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEGaussianBlurElement](../../aspose.svg.filters/svgfegaussianblurelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
