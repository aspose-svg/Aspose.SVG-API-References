---
title: "SVGFilterElementBuilder Class"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Builder.SVGFilterElementBuilder. Classe builder per la creazione di elementi filtro SVG che definiscono effetti di filtro applicabili alla grafica SVG."
type: docs
weight: 1440
url: /it/net/aspose.svg.builder/svgfilterelementbuilder/
---
## SVGFilterElementBuilder class

Classe Builder per creare elementi SVG 'filter', che definiscono effetti di filtro che possono essere applicati alla grafica SVG.

```csharp
public class SVGFilterElementBuilder : SVGElementBuilder<SVGFilterElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IFilterPrimitiveElementBuilder, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter, IRectAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGFilterElementBuilder](svgfilterelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfilterelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Aggiunge una configurazione script all'elemento filtro. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFilterElement](../../aspose.svg/svgfilterelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [FilterUnits](../../aspose.svg.builder/svgfilterelementbuilder/filterunits/)(*[CoordinateUnits](../coordinateunits/)*) | Imposta il sistema di coordinate per gli attributi x, y, width e height del filtro. |
| [PrimitiveUnits](../../aspose.svg.builder/svgfilterelementbuilder/primitiveunits/)(*[CoordinateUnits](../coordinateunits/)*) | Imposta il sistema di coordinate per i sotto-elementi primitivi del filtro. |

### Vedi anche

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFilterElement](../../aspose.svg/svgfilterelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IFilterPrimitiveElementBuilder](../ifilterprimitiveelementbuilder/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
