---
title: "Location‑Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Window.Location‑Klasse. Location‑Objekte stellen eine Darstellung der Adresse des aktiven Dokuments ihres Browsing‑Kontexts bereit und ermöglichen es, den aktuellen Eintrag des Sitzungsverlaufs des Browsing‑Kontexts zu ändern, indem Einträge im History‑Objekt hinzugefügt oder ersetzt werden."
type: docs
weight: 5950
url: /de/net/aspose.svg.window/location/
---
## Location class

Location‑Objekte bieten eine Darstellung der Adresse des aktiven Dokuments ihres Document's Browsing‑Kontexts und ermöglichen es, den aktuellen Eintrag des Sitzungsverlaufs des Browsing‑Kontexts zu ändern, indem Einträge im history object hinzugefügt oder ersetzt werden.

```csharp
public sealed class Location : DOMObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Hash](../../aspose.svg.window/location/hash/) { get; set; } | Gibt das Fragment der URL des Location‑Objekts zurück (enthält das führende „#“, falls nicht leer). Kann gesetzt werden, um zur gleichen URL mit geändertem Fragment zu navigieren (ignoriert das führende „#“). |
| [Host](../../aspose.svg.window/location/host/) { get; set; } | Gibt den Host und den Port der URL des Location‑Objekts zurück (falls vom Standardport des Schemas abweichend). Kann gesetzt werden, um zur gleichen URL mit geändertem Host und Port zu navigieren. |
| [Hostname](../../aspose.svg.window/location/hostname/) { get; set; } | Gibt den Host der URL des Location‑Objekts zurück. Kann gesetzt werden, um zur gleichen URL mit geändertem Host zu navigieren. |
| [Href](../../aspose.svg.window/location/href/) { get; set; } | Gibt die URL des Location‑Objekts zurück. Kann gesetzt werden, um zur angegebenen URL zu navigieren. |
| [Origin](../../aspose.svg.window/location/origin/) { get; } | Gibt den Ursprung der URL des Location‑Objekts zurück. |
| [Pathname](../../aspose.svg.window/location/pathname/) { get; set; } | Gibt den Pfad der URL des Location‑Objekts zurück. Kann gesetzt werden, um zur gleichen URL mit geändertem Pfad zu navigieren. |
| [Port](../../aspose.svg.window/location/port/) { get; set; } | Gibt den Port der URL des Location‑Objekts zurück. Kann gesetzt werden, um zur gleichen URL mit geändertem Port zu navigieren. |
| [Protocol](../../aspose.svg.window/location/protocol/) { get; set; } | Gibt das Schema der URL des Location‑Objekts zurück. Kann gesetzt werden, um zur gleichen URL mit geändertem Schema zu navigieren. |
| [Search](../../aspose.svg.window/location/search/) { get; set; } | Gibt die Abfrage der URL des Location‑Objekts zurück (enthält das führende „?“, falls nicht leer). Kann gesetzt werden, um zur gleichen URL mit geänderter Abfrage zu navigieren (ignoriert das führende „?“). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Assign](../../aspose.svg.window/location/assign/)(*string*) | Navigiert zur angegebenen Seite. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [Reload](../../aspose.svg.window/location/reload/)() | Lädt die aktuelle Seite neu. |
| [Replace](../../aspose.svg.window/location/replace/)(*string*) | Entfernt die aktuelle Seite aus dem Sitzungsverlauf und navigiert zur angegebenen Seite. |
| override [ToString](../../aspose.svg.window/location/tostring/)() | Gibt die URL des Location‑Objekts zurück. |

### Siehe auch

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
