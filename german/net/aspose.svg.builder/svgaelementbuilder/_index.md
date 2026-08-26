---
title: "SVGAElementBuilder Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.SVGAElementBuilder class. Builder‑Klasse zum Erstellen eines SVG‑a‑Elements, das zum Definieren von Hyperlinks verwendet wird. Sie ermöglicht das Erstellen von Inhalt innerhalb eines Elements und bietet Methoden zum Festlegen verschiedener Attribute, die speziell für das a‑Element in SVG gelten."
type: docs
weight: 1070
url: /de/net/aspose.svg.builder/svgaelementbuilder/
---
## SVGAElementBuilder class

Builder‑Klasse zum Erstellen eines SVG‑'a'-Elements, das zum Definieren von Hyperlinks verwendet wird. Sie ermöglicht das Erstellen von Inhalt innerhalb des 'a'-Elements und bietet Methoden zum Festlegen verschiedener, für das 'a'-Element in SVG spezifischer Attribute.

```csharp
public class SVGAElementBuilder : SVGElementBuilder<SVGAElement>, ICompositeAttributeSetter, 
    ICompositeElementBuilder
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SVGAElementBuilder](svgaelementbuilder/)() | Der Standard‑Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGAElement](../../aspose.svg/svgaelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Download](../../aspose.svg.builder/svgaelementbuilder/download/)(*string*) | Setzt das Attribut 'download' des SVG‑'a'-Elements und gibt an, dass der Link beim Aktivieren heruntergeladen wird. |
| [Href](../../aspose.svg.builder/svgaelementbuilder/href/)(*string*) | Setzt das Attribut 'href' des SVG‑'a'-Elements und gibt die URL der verlinkten Ressource an. |
| [HrefLang](../../aspose.svg.builder/svgaelementbuilder/hreflang/)(*string*) | Setzt das Attribut 'hreflang' des SVG‑'a'-Elements und gibt die Sprache der verlinkten Ressource an. |
| [Ping](../../aspose.svg.builder/svgaelementbuilder/ping/)(*string*) | Setzt das Attribut 'ping' des SVG‑'a'-Elements und enthält eine Liste von URLs, die benachrichtigt werden sollen, wenn dem Link gefolgt wird. |
| [ReferrerPolicy](../../aspose.svg.builder/svgaelementbuilder/referrerpolicy/)(*[ReferrerPolicy](../referrerpolicy/)*) | Setzt das Attribut 'referrerPolicy' des SVG-Elements 'a' und gibt an, wie viel des Referrers mit den Anfragen gesendet wird. |
| [Rel](../../aspose.svg.builder/svgaelementbuilder/rel/)(*string*) | Setzt das Attribut 'rel' des SVG-Elements 'a' und gibt die Beziehung des Zielobjekts zum Linkobjekt an. |
| [SetTarget](../../aspose.svg.builder/svgaelementbuilder/settarget/)(*string*) | Setzt das Attribut 'target' des SVG-Elements 'a' auf einen benutzerdefinierten XML-Namen. |
| [Type](../../aspose.svg.builder/svgaelementbuilder/type/)(*string*) | Setzt das Attribut 'type' des SVG-Elements 'a' und gibt den Medientyp der verlinkten Ressource an. |

### Siehe auch

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGAElement](../../aspose.svg/svgaelement/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
