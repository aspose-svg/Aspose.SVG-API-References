---
title: "SVGStyleElementBuilder-Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Builder.SVGStyleElementBuilder class. Eine Builder‑Klasse zum Erzeugen eines SVG‑Style‑Elements. Diese Klasse erleichtert die Erstellung und Konfiguration eines SVG‑Style‑Elements mit CSS‑Regeln."
type: docs
weight: 1630
url: /de/net/aspose.svg.builder/svgstyleelementbuilder/
---
## SVGStyleElementBuilder class

Eine Builder-Klasse zum Erstellen eines SVG-'style'-Elements. Diese Klasse erleichtert die Erstellung und Konfiguration eines SVG-Style-Elements mit CSS-Regeln.

```csharp
public class SVGStyleElementBuilder : SVGElementBuilder<SVGStyleElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SVGStyleElementBuilder](svgstyleelementbuilder/)() | Der Standard‑Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddComment](../../aspose.svg.builder/svgstyleelementbuilder/addcomment/)(*string*) | Fügt dem Style‑Inhalt einen Kommentar hinzu. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule)(*string, Action&lt;RuleBuilder&gt;*) | Fügt dem Style‑Element eine CSS‑Regel mithilfe eines RuleBuilders hinzu. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule_1)(*string, string*) | Fügt dem Style‑Element eine CSS‑Regel hinzu. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgstyleelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Erstellt das SVG‑Style‑Element mit den gesammelten CSS‑Regeln und fügt es dem angegebenen Dokument hinzu. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStyleElement](../../aspose.svg/svgstyleelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Media](../../aspose.svg.builder/svgstyleelementbuilder/media/)(*string*) | Legt das Attribut 'media' des SVG‑'style'-Elements fest. Dieses Attribut gibt das Medium an, für das die Stile vorgesehen sind, und ermöglicht, dass die Stile vom Medientyp abhängig sind. |
| [Title](../../aspose.svg.builder/svgstyleelementbuilder/title/)(*string*) | Legt das Attribut 'title' des SVG‑'style'-Elements fest. Dieses Attribut liefert einen Hinweis‑Titel für das Style‑Element, der für Barrierefreiheit und Tooltip‑Texte nützlich sein kann. |
| [Type](../../aspose.svg.builder/svgstyleelementbuilder/type/)(*string*) | Legt das Attribut 'type' des SVG‑'style'-Elements fest. Dieses Attribut gibt die Stylesheet‑Sprache des Inhalts des Elements an. |

### Siehe auch

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStyleElement](../../aspose.svg/svgstyleelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
