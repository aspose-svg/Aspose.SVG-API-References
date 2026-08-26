---
title: "SVGStopElementBuilder Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.SVGStopElementBuilder class. Builder‑Klasse zum Erstellen eines SVG‑Stop‑Elements. Das Stop‑Element wird innerhalb einer Farbverlaufsdefinition, entweder linear oder radial, verwendet, um Farb‑Stops zu definieren. Diese Klasse bietet Methoden zum Festlegen verschiedener für das Stop‑Element spezifischer Attribute wie Offset und Farbe."
type: docs
weight: 1620
url: /de/net/aspose.svg.builder/svgstopelementbuilder/
---
## SVGStopElementBuilder class

Builder-Klasse zum Erstellen eines SVG-'stop'-Elements. Das 'stop'-Element wird innerhalb einer Verlaufsdefinition (linear oder radial) verwendet, um Farbstopps zu definieren. Diese Klasse bietet Methoden zum Festlegen verschiedener Attribute, die speziell für das 'stop'-Element gelten, wie Offset und Farbe.

```csharp
public class SVGStopElementBuilder : SVGElementBuilder<SVGStopElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SVGStopElementBuilder](svgstopelementbuilder/)() | Der Standard‑Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgstopelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Fügt dem SVG‑'stop'-Element eine Skriptkonfiguration hinzu. |
| [AddStyle](../../aspose.svg.builder/svgstopelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Fügt dem SVG‑'stop'-Element eine Stilkonfiguration hinzu. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStopElement](../../aspose.svg/svgstopelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Offset](../../aspose.svg.builder/svgstopelementbuilder/offset/)(*double, [StopUnitType](../stopunittype/)*) | Setzt das Attribut 'offset' des SVG‑'stop'-Elements und gibt die Position des Farb‑Stops innerhalb des Farbverlaufs an. |

### Siehe auch

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStopElement](../../aspose.svg/svgstopelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
