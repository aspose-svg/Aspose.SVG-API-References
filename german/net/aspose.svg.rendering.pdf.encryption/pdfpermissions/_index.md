---
title: Enum PdfPermissions
second_title: Aspose.SVG für .NET-API-Referenz
description: Aspose.Svg.Rendering.Pdf.Encryption.PdfPermissions opsomming. Diese Aufzählung repräsentiert die Berechtigungen des Benutzers für ein PDF.
type: docs
weight: 2930
url: /de/net/aspose.svg.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Diese Aufzählung repräsentiert die Berechtigungen des Benutzers für ein PDF.

```csharp
[Flags]
public enum PdfPermissions
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| PrintDocument | `4` | (Sicherheitshandler der Revision 2) Drucken Sie das Dokument. (Sicherheitshandler der Revision 3 oder höher) Drucken Sie das Dokument (möglicherweise nicht auf der höchsten Qualitätsstufe, je nachdem, ob PrintingQuality ebenfalls eingestellt ist). |
| ModifyContent | `8` | Ändern Sie den Inhalt des Dokuments durch andere Operationen als die, die von ModifyTextAnnotations, FillForm und 11 gesteuert werden. |
| ExtractContent | `10` | Security Handler der Revision 2) Text und Grafiken aus dem Dokument kopieren oder anderweitig extrahieren, einschließlich des Extrahierens von Text und Grafiken (zur Unterstützung der Zugänglichkeit für Benutzer mit Behinderungen oder für andere Zwecke). (Security Handler der Revision 3 oder höher) Kopieren oder anderweitig Text und Grafiken aus dem Dokument durch andere Vorgänge als die von ExtractContentWithDisabilities. gesteuerten zu extrahieren. |
| ModifyTextAnnotations | `20` | Fügen Sie Textanmerkungen hinzu oder ändern Sie sie, füllen Sie interaktive Formularfelder aus und erstellen oder ändern Sie interaktive Formularfelder (einschließlich Signaturfelder), wenn ModifyContent ebenfalls festgelegt ist. |
| FillForm | `100` | (Sicherheitshandler der Revision 3 oder höher) Füllen Sie vorhandene interaktive Formularfelder (einschließlich Signaturfelder) aus, auch wenn ModifyTextAnnotations klar ist. |
| ExtractContentWithDisabilities | `200` | (Sicherheitshandler der Revision 3 oder höher) Text und Grafiken extrahieren (zur Unterstützung der Zugänglichkeit für Benutzer mit Behinderungen oder für andere Zwecke). |
| AssembleDocument | `400` | (Sicherheitshandler der Revision 3 oder höher) Das Dokument zusammenstellen (Seiten einfügen, drehen oder löschen und Lesezeichen oder Miniaturbilder erstellen), auch wenn ModifyContent klar ist. |
| PrintingQuality | `800` | (Sicherheitshandler der Revision 3 oder höher) Drucken Sie das Dokument in einer Darstellung, aus der eine originalgetreue digitale Kopie des PDF-Inhalts generiert werden könnte. Wenn dieses Bit gelöscht ist (und Bit 3 gesetzt ist), ist das Drucken auf niedrig begrenzt -Level-Darstellung des Aussehens, möglicherweise von verschlechterter Qualität. |

### Siehe auch

* namensraum [Aspose.Svg.Rendering.Pdf.Encryption](../../aspose.svg.rendering.pdf.encryption/)
* Montage [Aspose.SVG](../../)


