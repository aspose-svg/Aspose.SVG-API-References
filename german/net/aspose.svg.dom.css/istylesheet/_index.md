---
title: Interface IStyleSheet
second_title: Aspose.SVG für .NET-API-Referenz
description: Aspose.Svg.Dom.Css.IStyleSheet koppel. Die StyleSheetSchnittstelle ist die abstrakte Basisschnittstelle für jede Art von Stylesheet. Es stellt ein einzelnes Stylesheet dar das einem strukturierten Dokument zugeordnet ist.
type: docs
weight: 740
url: /de/net/aspose.svg.dom.css/istylesheet/
---
## IStyleSheet interface

Die StyleSheet-Schnittstelle ist die abstrakte Basisschnittstelle für jede Art von Stylesheet. Es stellt ein einzelnes Stylesheet dar, das einem strukturierten Dokument zugeordnet ist.

```csharp
public interface IStyleSheet
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Disabled](../../aspose.svg.dom.css/istylesheet/disabled/) { get; set; } | false, wenn das Stylesheet auf das Dokument angewendet wird. wahr, wenn nicht. Das Ändern dieses Attributs kann zu einer neuen Auflösung des Stils für das Dokument führen. Ein Stylesheet gilt nur, wenn sowohl eine geeignete Mediendefinition vorhanden ist als auch das Attribut disabled auf false gesetzt ist. Wenn also das Medium nicht auf den aktuellen Benutzeragenten zutrifft, wird das Attribut „disabled“ ignoriert. |
| [Href](../../aspose.svg.dom.css/istylesheet/href/) { get; } | Wenn das Stylesheet ein verknüpftes Stylesheet ist, ist der Wert seines Attributs sein Speicherort. Für Inline-Stylesheets ist der Wert dieses Attributs null. |
| [Media](../../aspose.svg.dom.css/istylesheet/media/) { get; } | Das beabsichtigte Zielmedium für Stilinformationen. |
| [OwnerNode](../../aspose.svg.dom.css/istylesheet/ownernode/) { get; } | Der Knoten, der dieses Stylesheet mit dem Dokument verknüpft. Bei HTML kann dies das entsprechende LINK- oder STYLE-Element sein. Bei XML kann dies die Verknüpfungsverarbeitungsanweisung sein. Für Stylesheets, die von anderen Stylesheets eingebunden werden, ist der Wert dieses Attributs null. |
| [ParentStyleSheet](../../aspose.svg.dom.css/istylesheet/parentstylesheet/) { get; } | Für Stylesheet-Sprachen, die das Konzept der Stylesheet-Inklusion unterstützen, stellt dieses Attribut das einschließende Stylesheet dar, sofern eines vorhanden ist. Wenn das Stylesheet ein Stylesheet der obersten Ebene ist oder die Stylesheet-Sprache die Einbindung nicht unterstützt, ist der Wert dieses Attributs null. |
| [Title](../../aspose.svg.dom.css/istylesheet/title/) { get; } | Der Beratungstitel. |
| [Type](../../aspose.svg.dom.css/istylesheet/type/) { get; } | Dies gibt die Stylesheet-Sprache für dieses Stylesheet an. Als Inhaltstyp wird die Stylesheet-Sprache angegeben (zB "text/css"). |

### Siehe auch

* namensraum [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* Montage [Aspose.SVG](../../)


