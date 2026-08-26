---
title: "ITrueTypeFont‑Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Drawing.ITrueTypeFont‑Schnittstelle. Deklariert Methoden zur Arbeit mit TrueType-Schriften"
type: docs
weight: 3540
url: /de/net/aspose.svg.drawing/itruetypefont/
---
## ITrueTypeFont interface

Deklariert Methoden zur Arbeit mit TrueType-Schriften.

```csharp
public interface ITrueTypeFont
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DataSize](../../aspose.svg.drawing/itruetypefont/datasize/) { get; } | Liest die Größe der Schriftartdaten in Bytes. |
| [FamilyName](../../aspose.svg.drawing/itruetypefont/familyname/) { get; } | Liest den Namen der Schriftfamilie. |
| [FullFontName](../../aspose.svg.drawing/itruetypefont/fullfontname/) { get; } | Der vollständige Schriftname wird im Allgemeinen als Kombination von Family- und Subfamily-Namen dargestellt. |
| [Style](../../aspose.svg.drawing/itruetypefont/style/) { get; } | Ermitteln Sie den Schriftstil, der die Werte der font-face-Regel und Daten aus der Schrift kombiniert. |
| [SubFamilyName](../../aspose.svg.drawing/itruetypefont/subfamilyname/) { get; } | Der Subfamily-Name unterscheidet die Schrift in einer Gruppe mit demselben Family-Namen. Es wird angenommen, dass er Stil (italic, oblique) und Gewicht (light, bold, black usw.) adressiert. Eine Schrift ohne besondere Unterschiede in Gewicht oder Stil sollte die Zeichenkette "Regular" haben. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetAscent](../../aspose.svg.drawing/itruetypefont/getascent/)(*float*) | Ermittelt den Aufstieg der Schrift in Punkten unter Verwendung der angegebenen Schriftgröße. |
| [GetData](../../aspose.svg.drawing/itruetypefont/getdata/)() | Öffnet den Stream mit den Schriftdaten. Der Aufrufer ist für das Freigeben des Streams verantwortlich. |
| [GetDescent](../../aspose.svg.drawing/itruetypefont/getdescent/)(*float*) | Ermittelt den Abstieg der Schrift in Punkten unter Verwendung der angegebenen Schriftgröße. |

### Siehe auch

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
