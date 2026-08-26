---
title: "SVGClipPathElementBuilder Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.SVGClipPathElementBuilder Klasse. Builder-Klasse zum Erstellen eines SVG clipPath-Elements, das zum Definieren eines Beschneidungspfads verwendet wird. Sie ermöglicht das Erstellen von Inhalt innerhalb des clipPath-Elements und bietet Methoden zum Festlegen verschiedener Attribute, die spezifisch für das clipPath-Element in SVG sind."
type: docs
weight: 1130
url: /de/net/aspose.svg.builder/svgclippathelementbuilder/
---
## SVGClipPathElementBuilder class

Builder-Klasse zum Erstellen eines SVG-'clipPath'-Elements, das zum Definieren eines Clipping-Pfads verwendet wird. Sie ermöglicht das Erstellen von Inhalt innerhalb des 'clipPath'-Elements und stellt Methoden zum Festlegen verschiedener, für das 'clipPath'-Element in SVG spezifischer Attribute bereit.

```csharp
public class SVGClipPathElementBuilder : SVGElementBuilder<SVGClipPathElement>, 
    IAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IShapeElementBuilder
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SVGClipPathElementBuilder](svgclippathelementbuilder/)() | Der Standard‑Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgclippathelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Fügt dem clipPath-Element ein Skript-Element hinzu. |
| [AddText](../../aspose.svg.builder/svgclippathelementbuilder/addtext/)(*Action&lt;SVGTextElementBuilder&gt;*) | Fügt dem clipPath-Element ein Text-Element hinzu. |
| [AddUse](../../aspose.svg.builder/svgclippathelementbuilder/adduse/)(*Action&lt;SVGUseElementBuilder&gt;*) | Fügt dem clipPath-Element ein 'use'-Element hinzu. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGClipPathElement](../../aspose.svg/svgclippathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [ClipPathUnits](../../aspose.svg.builder/svgclippathelementbuilder/clippathunits/)(*[CoordinateUnits](../coordinateunits/)*) | Setzt das Attribut 'clipPathUnits' des SVG 'clipPath'-Elements und gibt das Koordinatensystem für den Beschneidungspfad an. |

### Siehe auch

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGClipPathElement](../../aspose.svg/svgclippathelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IShapeElementBuilder](../ishapeelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
