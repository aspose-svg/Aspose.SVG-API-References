---
title: "SVGPatternElementBuilder Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.SVGPatternElementBuilder class. Builder-Klasse zum Erstellen eines SVG‑Pattern‑Elements, das verwendet wird, um ein Muster zu definieren, das zum Füllen von Grafikelementen innerhalb von SVG verwendet wird. Diese Klasse bietet Methoden zum Festlegen verschiedener Attribute, die spezifisch für das Pattern‑Element sind, und zum Erzeugen seines Inhalts."
type: docs
weight: 1540
url: /de/net/aspose.svg.builder/svgpatternelementbuilder/
---
## SVGPatternElementBuilder class

Builder-Klasse zum Erstellen eines SVG 'pattern'-Elements, das verwendet wird, um ein Muster zu definieren, das zum Füllen von Grafikelementen innerhalb von SVG verwendet wird. Diese Klasse bietet Methoden zum Festlegen verschiedener Attribute, die speziell für das 'pattern'-Element gelten, und zum Erstellen seines Inhalts.

```csharp
public class SVGPatternElementBuilder : SVGElementBuilder<SVGPatternElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, IRectAttributeSetter, 
    IViewBoxAttributeSetter
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SVGPatternElementBuilder](svgpatternelementbuilder/)() | Der Standard‑Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGPatternElement](../../aspose.svg/svgpatternelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgpatternelementbuilder/href/)(*string*) | Setzt das 'href'-Attribut des SVG-'pattern'-Elements und gibt eine Referenz zu einem anderen Muster an, von dem dieses Muster Attribute erbt. |
| [PatternContentUnits](../../aspose.svg.builder/svgpatternelementbuilder/patterncontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | Setzt das 'patternContentUnits'-Attribut des SVG-'pattern'-Elements und gibt das Koordinatensystem für den Inhalt des Musters an. |
| [PatternTransform](../../aspose.svg.builder/svgpatternelementbuilder/patterntransform/)(*Func&lt;TransformBuilder, TransformBuilder&gt;*) | Setzt das 'patternTransform'-Attribut des SVG-'pattern'-Elements und wendet eine Transformation auf das Muster an. |
| [PatternUnits](../../aspose.svg.builder/svgpatternelementbuilder/patternunits/)(*[CoordinateUnits](../coordinateunits/)*) | Setzt das 'patternUnits'-Attribut des SVG-'pattern'-Elements und gibt das Koordinatensystem für x, y, Breite und Höhe des Musters an. |

### Siehe auch

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
