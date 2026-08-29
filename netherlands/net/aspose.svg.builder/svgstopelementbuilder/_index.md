---
title: "SVGStopElementBuilder Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Builder.SVGStopElementBuilder klasse. Builderklasse voor het construeren van een SVG stop-element. Het stop-element wordt gebruikt binnen een gradientdefinitie, lineair of radiaal, om de kleuropties te definiëren. Deze klasse biedt methoden om verschillende attributen specifiek voor het stop-element in te stellen, zoals de offset en kleur."
type: docs
weight: 1620
url: /nl/net/aspose.svg.builder/svgstopelementbuilder/
---
## SVGStopElementBuilder class

Builder-klasse voor het construeren van een SVG 'stop'-element. Het 'stop'-element wordt gebruikt binnen een gradiëntdefinitie (lineair of radiaal) om de kleurstops te definiëren. Deze klasse biedt methoden om verschillende attributen specifiek voor het 'stop'-element in te stellen, zoals de offset en de kleur.

```csharp
public class SVGStopElementBuilder : SVGElementBuilder<SVGStopElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SVGStopElementBuilder](svgstopelementbuilder/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgstopelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Voegt een scriptconfiguratie toe aan het SVG 'stop'-element. |
| [AddStyle](../../aspose.svg.builder/svgstopelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Voegt een stijlconfiguratie toe aan het SVG 'stop'-element. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStopElement](../../aspose.svg/svgstopelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Offset](../../aspose.svg.builder/svgstopelementbuilder/offset/)(*double, [StopUnitType](../stopunittype/)*) | Stelt het 'offset'-attribuut van het SVG 'stop'-element in, waarmee de positie van de kleurstop binnen de gradient wordt gespecificeerd. |

### Zie ook

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStopElement](../../aspose.svg/svgstopelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
