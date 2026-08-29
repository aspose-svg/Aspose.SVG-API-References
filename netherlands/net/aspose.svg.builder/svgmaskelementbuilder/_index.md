---
title: "SVGMaskElementBuilder Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Builder.SVGMaskElementBuilder class. Builderklasse voor het construeren van een SVG-maskerelement dat wordt gebruikt om een alfacode te definiëren voor het compositeren van het huidige object in de achtergrond. Deze klasse maakt het mogelijk om inhoud binnen het maskerelement te bouwen en biedt methoden om verschillende attributen die specifiek zijn voor het maskerelement in SVG in te stellen."
type: docs
weight: 1510
url: /nl/net/aspose.svg.builder/svgmaskelementbuilder/
---
## SVGMaskElementBuilder class

Builder-klasse voor het construeren van een SVG 'mask'-element, dat wordt gebruikt om een alfabeta-masker te definiëren voor het compositeren van het huidige object in de achtergrond. Deze klasse maakt het mogelijk om inhoud binnen het 'mask'-element op te bouwen en biedt methoden om verschillende attributen specifiek voor het 'mask'-element in SVG in te stellen.

```csharp
public class SVGMaskElementBuilder : SVGElementBuilder<SVGMaskElement>, ICompositeElementBuilder, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IRectAttributeSetter
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SVGMaskElementBuilder](svgmaskelementbuilder/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMaskElement](../../aspose.svg/svgmaskelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MaskContentUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskcontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | Stelt het 'maskContentUnits'-attribuut van het SVG 'mask'-element in, waarbij het coördinatensysteem voor de inhoud van het masker wordt gespecificeerd. |
| [MaskUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskunits/)(*[CoordinateUnits](../coordinateunits/)*) | Stelt het 'maskUnits'-attribuut van het SVG 'mask'-element in, waarbij het coördinatensysteem voor de attributen van het masker wordt gespecificeerd. |

### Zie ook

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGMaskElement](../../aspose.svg/svgmaskelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../iconditionalprocessingattributesetter/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
