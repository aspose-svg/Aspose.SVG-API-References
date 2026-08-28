---
title: "SVGFEDropShadowElementBuilder Class"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Builder.SVGFEDropShadowElementBuilder. Classe builder per la creazione di elementi SVG feDropShadow utilizzati nei filtri SVG per applicare un effetto di ombra."
type: docs
weight: 1270
url: /it/net/aspose.svg.builder/svgfedropshadowelementbuilder/
---
## SVGFEDropShadowElementBuilder class

Classe Builder per la creazione di elementi SVG 'feDropShadow', utilizzati nei filtri SVG per applicare un effetto di ombra portata.

```csharp
public class SVGFEDropShadowElementBuilder : SVGElementBuilder<SVGFEDropShadowElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGFEDropShadowElementBuilder](svgfedropshadowelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfedropshadowelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Aggiunge una configurazione script all'elemento feDropShadow. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEDropShadowElement](../../aspose.svg.filters/svgfedropshadowelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Dx](../../aspose.svg.builder/svgfedropshadowelementbuilder/dx/)(*double*) | Imposta lo spostamento orizzontale ('dx') per l'ombra. |
| [Dy](../../aspose.svg.builder/svgfedropshadowelementbuilder/dy/)(*double*) | Imposta lo spostamento verticale ('dy') per l'ombra. |
| [StdDeviation](../../aspose.svg.builder/svgfedropshadowelementbuilder/stddeviation/)(*double, double?*) | Imposta la deviazione standard per l'effetto di sfocatura nell'ombra. |

### Vedi anche

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEDropShadowElement](../../aspose.svg.filters/svgfedropshadowelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
