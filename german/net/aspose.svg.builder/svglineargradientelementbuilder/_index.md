---
title: "SVGLinearGradientElementBuilder Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.SVGLinearGradientElementBuilder Klasse. Builder-Klasse zum Erstellen eines SVG linearGradient-Elements, das verwendet wird, um einen linearen Farbverlauf innerhalb von SVG-Grafiken zu definieren. Sie ermöglicht das Erstellen von Inhalt innerhalb des linearGradient-Elements und bietet Methoden zum Setzen verschiedener, spezifischer Attribute des linearGradient-Elements in SVG."
type: docs
weight: 1490
url: /de/net/aspose.svg.builder/svglineargradientelementbuilder/
---
## SVGLinearGradientElementBuilder class

Builder-Klasse zum Erstellen eines SVG 'linearGradient'-Elements, das verwendet wird, um einen linearen Farbverlauf innerhalb von SVG-Grafiken zu definieren. Sie ermöglicht das Erstellen von Inhalten innerhalb des 'linearGradient'-Elements und bietet Methoden zum Festlegen verschiedener Attribute, die speziell für das 'linearGradient'-Element in SVG gelten.

```csharp
public class SVGLinearGradientElementBuilder : SVGElementBuilder<SVGLinearGradientElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, IGradientStopElementBuilder, 
    IPresentationAttributeSetter
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SVGLinearGradientElementBuilder](svglineargradientelementbuilder/)() | Der Standard‑Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddAnimateTransform](../../aspose.svg.builder/svglineargradientelementbuilder/addanimatetransform/)(*Action&lt;SVGAnimateTransformElementBuilder&gt;*) | Fügt dem SVG 'linearGradient'-Element eine Animate-Transform-Konfiguration hinzu. |
| [AddScript](../../aspose.svg.builder/svglineargradientelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Fügt dem SVG 'linearGradient'-Element eine Skriptkonfiguration hinzu. |
| [AddStyle](../../aspose.svg.builder/svglineargradientelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Fügt dem SVG 'linearGradient'-Element eine Stilkonfiguration hinzu. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGLinearGradientElement](../../aspose.svg/svglineargradientelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svglineargradientelementbuilder/href/)(*string*) | Setzt das Attribut 'href' des SVG 'linearGradient'-Elements und gibt einen Verweis auf einen anderen Farbverlauf an. |
| [X1](../../aspose.svg.builder/svglineargradientelementbuilder/x1/)(*double, [LengthType](../lengthtype/)*) | Setzt das Attribut 'x1' des SVG-Elements 'linearGradient', das die x‑Koordinate des Startpunkts des Farbverlaufs angibt. |
| [X2](../../aspose.svg.builder/svglineargradientelementbuilder/x2/)(*double, [LengthType](../lengthtype/)*) | Setzt das Attribut 'x2' des SVG-Elements 'linearGradient', das die x‑Koordinate des Endpunkts des Farbverlaufs angibt. |
| [Y1](../../aspose.svg.builder/svglineargradientelementbuilder/y1/)(*double, [LengthType](../lengthtype/)*) | Setzt das Attribut 'y1' des SVG-Elements 'linearGradient', das die y‑Koordinate des Startpunkts des Farbverlaufs angibt. |
| [Y2](../../aspose.svg.builder/svglineargradientelementbuilder/y2/)(*double, [LengthType](../lengthtype/)*) | Setzt das Attribut 'y2' des SVG-Elements 'linearGradient', das die y‑Koordinate des Endpunkts des Farbverlaufs angibt. |

### Siehe auch

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
