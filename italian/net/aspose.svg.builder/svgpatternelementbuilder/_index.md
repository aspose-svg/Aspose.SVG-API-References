---
title: "Classe SVGPatternElementBuilder"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Builder.SVGPatternElementBuilder. Classe builder per la costruzione di un elemento pattern SVG, utilizzato per definire un pattern da usare per riempire gli elementi grafici all'interno di SVG. Questa classe fornisce metodi per impostare vari attributi specifici dell'elemento pattern e per costruirne il contenuto."
type: docs
weight: 1540
url: /it/net/aspose.svg.builder/svgpatternelementbuilder/
---
## SVGPatternElementBuilder class

Classe Builder per costruire un elemento SVG 'pattern', che è usato per definire un motivo da utilizzare per riempire gli elementi grafici all'interno di SVG. Questa classe fornisce metodi per impostare vari attributi specifici dell'elemento 'pattern' e per costruirne il contenuto.

```csharp
public class SVGPatternElementBuilder : SVGElementBuilder<SVGPatternElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, IRectAttributeSetter, 
    IViewBoxAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGPatternElementBuilder](svgpatternelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGPatternElement](../../aspose.svg/svgpatternelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgpatternelementbuilder/href/)(*string*) | Imposta l'attributo 'href' dell'elemento SVG 'pattern', specificando un riferimento a un altro pattern da cui questo pattern eredita gli attributi. |
| [PatternContentUnits](../../aspose.svg.builder/svgpatternelementbuilder/patterncontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | Imposta l'attributo 'patternContentUnits' dell'elemento SVG 'pattern', specificando il sistema di coordinate per il contenuto del pattern. |
| [PatternTransform](../../aspose.svg.builder/svgpatternelementbuilder/patterntransform/)(*Func&lt;TransformBuilder, TransformBuilder&gt;*) | Imposta l'attributo 'patternTransform' dell'elemento SVG 'pattern', applicando una trasformazione al pattern. |
| [PatternUnits](../../aspose.svg.builder/svgpatternelementbuilder/patternunits/)(*[CoordinateUnits](../coordinateunits/)*) | Imposta l'attributo 'patternUnits' dell'elemento SVG 'pattern', specificando il sistema di coordinate per x, y, larghezza e altezza del pattern. |

### Vedi anche

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGPatternElement](../../aspose.svg/svgpatternelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
