---
title: "SVGScriptElementBuilder Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.SVGScriptElementBuilder Klasse. Builder‑Klasse zum Erstellen eines SVG‑Skript‑Elements. Das Skript‑Element wird verwendet, um ausführbare Skripte in SVG‑Dokumenten einzubetten oder zu referenzieren. Diese Klasse bietet Methoden zum Festlegen verschiedener, für das Skript‑Element spezifischer Attribute wie Typ, Quelle und Cross‑Origin‑Einstellungen."
type: docs
weight: 1600
url: /de/net/aspose.svg.builder/svgscriptelementbuilder/
---
## SVGScriptElementBuilder class

Builder-Klasse zum Erstellen eines SVG-'script'-Elements. Das 'script'-Element wird verwendet, um ausführbare Skripte in SVG-Dokumenten einzubetten oder zu referenzieren. Diese Klasse bietet Methoden zum Festlegen verschiedener Attribute, die speziell für das 'script'-Element gelten, wie Typ, Quelle und Cross-Origin-Einstellungen.

```csharp
public class SVGScriptElementBuilder : SVGElementBuilder<SVGScriptElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SVGScriptElementBuilder](svgscriptelementbuilder/)() | Der Standard‑Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGScriptElement](../../aspose.svg/svgscriptelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Crossorigin](../../aspose.svg.builder/svgscriptelementbuilder/crossorigin/)(*string*) | Setzt das Attribut 'crossorigin' des SVG-'script'-Elements und gibt die CORS-Einstellungen für das externe Skript an. |
| [Href](../../aspose.svg.builder/svgscriptelementbuilder/href/)(*string*) | Setzt das Attribut 'href' des SVG-'script'-Elements und gibt die URL einer externen Skriptdatei an. |
| [Type](../../aspose.svg.builder/svgscriptelementbuilder/type/)(*string*) | Setzt das Attribut 'type' des SVG-'script'-Elements und gibt den Typ der Skriptsprache an (z. B. "text/javascript"). |

### Siehe auch

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGScriptElement](../../aspose.svg/svgscriptelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
