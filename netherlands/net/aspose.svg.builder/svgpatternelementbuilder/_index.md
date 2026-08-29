---
title: "SVGPatternElementBuilder Class"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Builder.SVGPatternElementBuilder class. Builderklasse voor het construeren van een SVG-patroonelement dat wordt gebruikt om een patroon te definiëren dat wordt gebruikt voor het vullen van grafische elementen binnen SVG. Deze klasse biedt methoden om verschillende attributen specifiek voor het patroonelement in te stellen en om de inhoud ervan op te bouwen."
type: docs
weight: 1540
url: /nl/net/aspose.svg.builder/svgpatternelementbuilder/
---
## SVGPatternElementBuilder class

Builder-klasse voor het construeren van een SVG 'pattern'-element, dat wordt gebruikt om een patroon te definiëren dat wordt gebruikt om grafische elementen binnen SVG te vullen. Deze klasse biedt methoden om verschillende attributen specifiek voor het 'pattern'-element in te stellen en om de inhoud ervan op te bouwen.

```csharp
public class SVGPatternElementBuilder : SVGElementBuilder<SVGPatternElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, IRectAttributeSetter, 
    IViewBoxAttributeSetter
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SVGPatternElementBuilder](svgpatternelementbuilder/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGPatternElement](../../aspose.svg/svgpatternelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgpatternelementbuilder/href/)(*string*) | Stelt het 'href'-attribuut van het SVG 'pattern'-element in, waarbij een verwijzing naar een ander patroon wordt gespecificeerd waarvan dit patroon attributen erft. |
| [PatternContentUnits](../../aspose.svg.builder/svgpatternelementbuilder/patterncontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | Stelt het 'patternContentUnits'-attribuut van het SVG 'pattern'-element in, waarmee het coördinatensysteem voor de inhoud van het patroon wordt gespecificeerd. |
| [PatternTransform](../../aspose.svg.builder/svgpatternelementbuilder/patterntransform/)(*Func&lt;TransformBuilder, TransformBuilder&gt;*) | Stelt het 'patternTransform'-attribuut van het SVG 'pattern'-element in, waardoor een transformatie op het patroon wordt toegepast. |
| [PatternUnits](../../aspose.svg.builder/svgpatternelementbuilder/patternunits/)(*[CoordinateUnits](../coordinateunits/)*) | Stelt het 'patternUnits'-attribuut van het SVG 'pattern'-element in, waarmee het coördinatensysteem voor de x-, y-, breedte- en hoogtewaarden van het patroon wordt gespecificeerd. |

### Zie ook

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
