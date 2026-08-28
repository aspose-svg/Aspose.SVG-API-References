---
title: "SVGFETurbulenceElementBuilder Class"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Aspose.Svg.Builder.SVGFETurbulenceElementBuilder class. Classe builder per la creazione di elementi SVG feTurbulence che generano un'immagine usando la funzione di turbolenza di Perlin"
type: docs
weight: 1430
url: /it/net/aspose.svg.builder/svgfeturbulenceelementbuilder/
---
## SVGFETurbulenceElementBuilder class

Classe Builder per creare elementi SVG 'feTurbulence', che generano un'immagine usando la funzione di turbolenza di Perlin.

```csharp
public class SVGFETurbulenceElementBuilder : SVGElementBuilder<SVGFETurbulenceElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGFETurbulenceElementBuilder](svgfeturbulenceelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfeturbulenceelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Aggiunge una configurazione di script all'elemento feTurbulence. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| [BaseFrequency](../../aspose.svg.builder/svgfeturbulenceelementbuilder/basefrequency/)(*double, double?*) | Imposta la frequenza di base per la funzione di turbolenza. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFETurbulenceElement](../../aspose.svg.filters/svgfeturbulenceelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [NumOctaves](../../aspose.svg.builder/svgfeturbulenceelementbuilder/numoctaves/)(*int*) | Imposta il numero di ottave per la funzione di turbolenza. |
| [Seed](../../aspose.svg.builder/svgfeturbulenceelementbuilder/seed/)(*double*) | Imposta il seme per il generatore di numeri casuali utilizzato dalla funzione di turbolenza. |
| [StitchTiles](../../aspose.svg.builder/svgfeturbulenceelementbuilder/stitchtiles/)(*[StitchTiles](../stitchtiles/)*) | Imposta l'opzione stitch tiles per la funzione di turbolenza. |
| [Type](../../aspose.svg.builder/svgfeturbulenceelementbuilder/type/)(*[TurbulenceType](../turbulencetype/)*) | Imposta il tipo di turbolenza (rumore frattale o turbolenza). |

### Vedi anche

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFETurbulenceElement](../../aspose.svg.filters/svgfeturbulenceelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
