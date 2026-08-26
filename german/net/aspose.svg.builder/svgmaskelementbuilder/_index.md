---
title: "SVGMaskElementBuilder Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.SVGMaskElementBuilder Klasse. Builder-Klasse zum Erstellen eines SVG-Maskenelements, das verwendet wird, um eine Alphamaske für die Komposition des aktuellen Objekts in den Hintergrund zu definieren. Diese Klasse ermöglicht das Erstellen von Inhalt innerhalb des Maskenelements und bietet Methoden zum Festlegen verschiedener, für das Maskenelement in SVG spezifischer Attribute."
type: docs
weight: 1510
url: /de/net/aspose.svg.builder/svgmaskelementbuilder/
---
## SVGMaskElementBuilder class

Builder-Klasse zum Erstellen eines SVG 'mask'-Elements, das verwendet wird, um eine Alpha-Maske für die Komposition des aktuellen Objekts in den Hintergrund zu definieren. Diese Klasse ermöglicht das Erstellen von Inhalten innerhalb des 'mask'-Elements und bietet Methoden zum Festlegen verschiedener Attribute, die speziell für das 'mask'-Element in SVG gelten.

```csharp
public class SVGMaskElementBuilder : SVGElementBuilder<SVGMaskElement>, ICompositeElementBuilder, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IRectAttributeSetter
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SVGMaskElementBuilder](svgmaskelementbuilder/)() | Der Standard‑Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMaskElement](../../aspose.svg/svgmaskelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MaskContentUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskcontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | Setzt das Attribut 'maskContentUnits' des SVG-'mask'-Elements und gibt das Koordinatensystem für den Inhalt der Maske an. |
| [MaskUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskunits/)(*[CoordinateUnits](../coordinateunits/)*) | Setzt das Attribut 'maskUnits' des SVG-'mask'-Elements und gibt das Koordinatensystem für die Attribute der Maske an. |

### Siehe auch

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
