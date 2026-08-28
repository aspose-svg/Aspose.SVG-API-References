---
title: "Classe SVGLinearGradientElementBuilder"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Builder.SVGLinearGradientElementBuilder. Classe Builder per la costruzione di un elemento SVG linearGradient utilizzato per definire un gradiente lineare all'interno della grafica SVG. Consente la creazione di contenuti all'interno dell'elemento linearGradient e fornisce metodi per impostare vari attributi specifici dell'elemento linearGradient in SVG"
type: docs
weight: 1490
url: /it/net/aspose.svg.builder/svglineargradientelementbuilder/
---
## SVGLinearGradientElementBuilder class

Classe Builder per costruire un elemento SVG 'linearGradient', che è usato per definire un gradiente lineare nella grafica SVG. Consente la costruzione del contenuto all'interno dell'elemento 'linearGradient' e fornisce metodi per impostare vari attributi specifici dell'elemento 'linearGradient' in SVG.

```csharp
public class SVGLinearGradientElementBuilder : SVGElementBuilder<SVGLinearGradientElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, IGradientStopElementBuilder, 
    IPresentationAttributeSetter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SVGLinearGradientElementBuilder](svglineargradientelementbuilder/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddAnimateTransform](../../aspose.svg.builder/svglineargradientelementbuilder/addanimatetransform/)(*Action&lt;SVGAnimateTransformElementBuilder&gt;*) | Aggiunge una configurazione di animazione di trasformazione all'elemento SVG 'linearGradient'. |
| [AddScript](../../aspose.svg.builder/svglineargradientelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Aggiunge una configurazione di script all'elemento SVG 'linearGradient'. |
| [AddStyle](../../aspose.svg.builder/svglineargradientelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Aggiunge una configurazione di stile all'elemento SVG 'linearGradient'. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGLinearGradientElement](../../aspose.svg/svglineargradientelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svglineargradientelementbuilder/href/)(*string*) | Imposta l'attributo 'href' dell'elemento SVG 'linearGradient', specificando un riferimento a un altro gradiente. |
| [X1](../../aspose.svg.builder/svglineargradientelementbuilder/x1/)(*double, [LengthType](../lengthtype/)*) | Imposta l'attributo 'x1' dell'elemento SVG 'linearGradient', specificando la coordinata x del punto di inizio del gradiente. |
| [X2](../../aspose.svg.builder/svglineargradientelementbuilder/x2/)(*double, [LengthType](../lengthtype/)*) | Imposta l'attributo 'x2' dell'elemento SVG 'linearGradient', specificando la coordinata x del punto finale del gradiente. |
| [Y1](../../aspose.svg.builder/svglineargradientelementbuilder/y1/)(*double, [LengthType](../lengthtype/)*) | Imposta l'attributo 'y1' dell'elemento SVG 'linearGradient', specificando la coordinata y del punto di inizio del gradiente. |
| [Y2](../../aspose.svg.builder/svglineargradientelementbuilder/y2/)(*double, [LengthType](../lengthtype/)*) | Imposta l'attributo 'y2' dell'elemento SVG 'linearGradient', specificando la coordinata y del punto finale del gradiente. |

### Vedi anche

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGLinearGradientElement](../../aspose.svg/svglineargradientelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IGradientStopElementBuilder](../igradientstopelementbuilder/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
