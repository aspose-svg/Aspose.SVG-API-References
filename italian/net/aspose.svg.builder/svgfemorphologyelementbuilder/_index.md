---
title: "SVGFEMorphologyElementBuilder Classe"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Aspose.Svg.Builder.SVGFEMorphologyElementBuilder classe. Classe builder per creare elementi SVG feMorphology che sono usati per applicare operazioni morfologiche come dilatazione o erosione su un'immagine di input"
type: docs
weight: 1370
url: /it/net/aspose.svg.builder/svgfemorphologyelementbuilder/
---
## SVGFEMorphologyElementBuilder class

Classe Builder per creare elementi SVG 'feMorphology', che sono usati per applicare operazioni morfologiche come dilatazione o erosione su un'immagine di input.

```csharp
public class SVGFEMorphologyElementBuilder : SVGElementBuilder<SVGFEMorphologyElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGFEMorphologyElementBuilder](svgfemorphologyelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfemorphologyelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Aggiunge una configurazione di script all'elemento feMorphology. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEMorphologyElement](../../aspose.svg.filters/svgfemorphologyelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Operator](../../aspose.svg.builder/svgfemorphologyelementbuilder/operator/)(*[MorphologyOperator](../morphologyoperator/)*) | Imposta l'attributo 'operator' dell'elemento feMorphology, specificando il tipo di operazione morfologica. |
| [Radius](../../aspose.svg.builder/svgfemorphologyelementbuilder/radius/)(*double, double?*) | Imposta l'attributo 'radius' dell'elemento feMorphology, definendo il raggio per l'operazione morfologica. |

### Vedi anche

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEMorphologyElement](../../aspose.svg.filters/svgfemorphologyelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
