---
title: "SVGFETurbulenceElementBuilder Class"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Builder.SVGFETurbulenceElementBuilder class. Builderklasse voor het maken van SVG feTurbulence-elementen die een afbeelding creëren met behulp van de Perlin‑turbulatiefunctie"
type: docs
weight: 1430
url: /nl/net/aspose.svg.builder/svgfeturbulenceelementbuilder/
---
## SVGFETurbulenceElementBuilder class

Builder-klasse voor het maken van SVG 'feTurbulence'-elementen, die een afbeelding creëren met behulp van de Perlin‑turbulentiefunctie.

```csharp
public class SVGFETurbulenceElementBuilder : SVGElementBuilder<SVGFETurbulenceElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SVGFETurbulenceElementBuilder](svgfeturbulenceelementbuilder/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfeturbulenceelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Voegt een scriptconfiguratie toe aan het feTurbulence-element. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| [BaseFrequency](../../aspose.svg.builder/svgfeturbulenceelementbuilder/basefrequency/)(*double, double?*) | Stelt de basisfrequentie in voor de turbulatiefunctie. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFETurbulenceElement](../../aspose.svg.filters/svgfeturbulenceelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [NumOctaves](../../aspose.svg.builder/svgfeturbulenceelementbuilder/numoctaves/)(*int*) | Stelt het aantal octaven in voor de turbulentiefunctie. |
| [Seed](../../aspose.svg.builder/svgfeturbulenceelementbuilder/seed/)(*double*) | Stelt de seed in voor de willekeurige getalgenerator die door de turbulentiefunctie wordt gebruikt. |
| [StitchTiles](../../aspose.svg.builder/svgfeturbulenceelementbuilder/stitchtiles/)(*[StitchTiles](../stitchtiles/)*) | Stelt de optie 'stitch tiles' in voor de turbulentiefunctie. |
| [Type](../../aspose.svg.builder/svgfeturbulenceelementbuilder/type/)(*[TurbulenceType](../turbulencetype/)*) | Stelt het type turbulentie in (fractal noise of turbulentie). |

### Zie ook

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFETurbulenceElement](../../aspose.svg.filters/svgfeturbulenceelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
