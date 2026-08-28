---
title: "Classe SVGClipPathElementBuilder"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Builder.SVGClipPathElementBuilder. Classe builder per costruire un elemento SVG clipPath utilizzato per definire un percorso di ritaglio. Consente la costruzione di contenuti all'interno dell'elemento clipPath e fornisce metodi per impostare vari attributi specifici dell'elemento clipPath in SVG."
type: docs
weight: 1130
url: /it/net/aspose.svg.builder/svgclippathelementbuilder/
---
## SVGClipPathElementBuilder class

Classe Builder per la costruzione di un elemento SVG 'clipPath', utilizzato per definire un percorso di ritaglio. Consente la creazione di contenuti all'interno dell'elemento 'clipPath' e fornisce metodi per impostare vari attributi specifici dell'elemento 'clipPath' in SVG.

```csharp
public class SVGClipPathElementBuilder : SVGElementBuilder<SVGClipPathElement>, 
    IAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IShapeElementBuilder
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGClipPathElementBuilder](svgclippathelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgclippathelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Aggiunge un elemento script all'elemento clipPath. |
| [AddText](../../aspose.svg.builder/svgclippathelementbuilder/addtext/)(*Action&lt;SVGTextElementBuilder&gt;*) | Aggiunge un elemento text all'elemento clipPath. |
| [AddUse](../../aspose.svg.builder/svgclippathelementbuilder/adduse/)(*Action&lt;SVGUseElementBuilder&gt;*) | Aggiunge un elemento 'use' all'elemento clipPath. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGClipPathElement](../../aspose.svg/svgclippathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [ClipPathUnits](../../aspose.svg.builder/svgclippathelementbuilder/clippathunits/)(*[CoordinateUnits](../coordinateunits/)*) | Imposta l'attributo 'clipPathUnits' dell'elemento SVG 'clipPath', specificando il sistema di coordinate per il percorso di ritaglio. |

### Vedi anche

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGClipPathElement](../../aspose.svg/svgclippathelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IShapeElementBuilder](../ishapeelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
