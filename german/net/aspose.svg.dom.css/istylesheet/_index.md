---
title: "IStyleSheet Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Css.IStyleSheet Schnittstelle. Die StyleSheet‑Schnittstelle ist die abstrakte Basisschnittstelle für jede Art von Stylesheet. Sie repräsentiert ein einzelnes Stylesheet, das mit einem strukturierten Dokument verknüpft ist"
type: docs
weight: 2740
url: /de/net/aspose.svg.dom.css/istylesheet/
---
## IStyleSheet interface

Die StyleSheet-Schnittstelle ist die abstrakte Basisschnittstelle für jede Art von Stylesheet. Sie stellt ein einzelnes Stylesheet dar, das mit einem strukturierten Dokument verknüpft ist.

```csharp
public interface IStyleSheet
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Disabled](../../aspose.svg.dom.css/istylesheet/disabled/) { get; set; } | false, wenn das Stylesheet auf das Dokument angewendet wird. true, wenn dies nicht der Fall ist. Das Ändern dieses Attributs kann zu einer erneuten Auflösung des Stils für das Dokument führen. Ein Stylesheet wird nur angewendet, wenn sowohl eine passende Medientypdefinition vorhanden ist als auch das Attribut disabled den Wert false hat. Wenn das Medium also nicht auf den aktuellen User‑Agent zutrifft, wird das disabled‑Attribut ignoriert. |
| [Href](../../aspose.svg.dom.css/istylesheet/href/) { get; } | Wenn das Stylesheet ein verknüpftes Stylesheet ist, ist der Wert seines Attributs sein Speicherort. Für Inline‑Stylesheets ist der Wert dieses Attributs null. |
| [Media](../../aspose.svg.dom.css/istylesheet/media/) { get; } | Das beabsichtigte Zielmedium für Stilinformationen. |
| [OwnerNode](../../aspose.svg.dom.css/istylesheet/ownernode/) { get; } | Der Knoten, der dieses Stylesheet mit dem Dokument verknüpft. Für HTML kann dies das entsprechende LINK‑ oder STYLE‑Element sein. Für XML kann es die verknüpfende Verarbeitungsanweisung sein. Für Stylesheets, die von anderen Stylesheets eingebunden werden, ist der Wert dieses Attributs null. |
| [ParentStyleSheet](../../aspose.svg.dom.css/istylesheet/parentstylesheet/) { get; } | Für Stylesheet‑Sprachen, die das Konzept der Stylesheet‑Einbindung unterstützen, repräsentiert dieses Attribut das einbindende Stylesheet, falls eines existiert. Ist das Stylesheet ein Top‑Level‑Stylesheet oder unterstützt die Stylesheet‑Sprache keine Einbindung, ist der Wert dieses Attributs null. |
| [Title](../../aspose.svg.dom.css/istylesheet/title/) { get; } | Der Hinweis‑Titel. |
| [Type](../../aspose.svg.dom.css/istylesheet/type/) { get; } | Dies gibt die Stylesheet‑Sprache für dieses Stylesheet an. Die Stylesheet‑Sprache wird als Content‑Typ angegeben (z. B. "text/css"). |

### Siehe auch

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
