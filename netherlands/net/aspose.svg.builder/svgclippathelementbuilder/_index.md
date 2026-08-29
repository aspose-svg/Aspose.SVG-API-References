---
title: "SVGClipPathElementBuilder Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Builder.SVGClipPathElementBuilder class. Builderklasse voor het construeren van een SVG clipPath-element dat wordt gebruikt om een knippad te definiëren. Het maakt het mogelijk om inhoud binnen het clipPath-element te bouwen en biedt methoden om verschillende attributen die specifiek zijn voor het clipPath-element in SVG in te stellen."
type: docs
weight: 1130
url: /nl/net/aspose.svg.builder/svgclippathelementbuilder/
---
## SVGClipPathElementBuilder class

Builderklasse voor het construeren van een SVG 'clipPath'-element, dat wordt gebruikt om een knippad te definiëren. Het maakt het mogelijk om inhoud binnen het 'clipPath'-element te bouwen en biedt methoden om verschillende attributen in te stellen die specifiek zijn voor het 'clipPath'-element in SVG.

```csharp
public class SVGClipPathElementBuilder : SVGElementBuilder<SVGClipPathElement>, 
    IAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IShapeElementBuilder
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SVGClipPathElementBuilder](svgclippathelementbuilder/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgclippathelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Voegt een script‑element toe aan het clipPath‑element. |
| [AddText](../../aspose.svg.builder/svgclippathelementbuilder/addtext/)(*Action&lt;SVGTextElementBuilder&gt;*) | Voegt een tekst‑element toe aan het clipPath‑element. |
| [AddUse](../../aspose.svg.builder/svgclippathelementbuilder/adduse/)(*Action&lt;SVGUseElementBuilder&gt;*) | Voegt een 'use'-element toe aan het clipPath‑element. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGClipPathElement](../../aspose.svg/svgclippathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [ClipPathUnits](../../aspose.svg.builder/svgclippathelementbuilder/clippathunits/)(*[CoordinateUnits](../coordinateunits/)*) | Stelt het 'clipPathUnits'-attribuut van het SVG 'clipPath'-element in, waarmee het coördinatensysteem voor het knippad wordt gespecificeerd. |

### Zie ook

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGClipPathElement](../../aspose.svg/svgclippathelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IShapeElementBuilder](../ishapeelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
