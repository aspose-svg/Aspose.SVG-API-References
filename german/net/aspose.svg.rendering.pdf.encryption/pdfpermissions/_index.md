---
title: "PdfPermissions Aufzählung"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Rendering.Pdf.Encryption.PdfPermissions Aufzählung. Diese Aufzählung stellt die Benutzerberechtigungen für ein PDF dar."
type: docs
weight: 5000
url: /de/net/aspose.svg.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Dieses Enum repräsentiert die Berechtigungen des Benutzers für ein PDF.

```csharp
[Flags]
public enum PdfPermissions
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| PrintDocument | `4` | (Sicherheits-Handler der Revision 2) Dokument drucken. (Sicherheits-Handler der Revision 3 oder höher) Dokument drucken (möglicherweise nicht in höchster Qualität, abhängig davon, ob PrintingQuality ebenfalls gesetzt ist). |
| ModifyContent | `8` | Den Inhalt des Dokuments durch Vorgänge ändern, die nicht von ModifyTextAnnotations, FillForm und 11 gesteuert werden. |
| ExtractContent | `10` | (Sicherheits-Handler der Revision 2) Text und Grafiken aus dem Dokument kopieren oder anderweitig extrahieren, einschließlich des Extrahierens von Text und Grafiken (zur Unterstützung der Barrierefreiheit für Nutzer mit Behinderungen oder zu anderen Zwecken). (Sicherheits-Handler der Revision 3 oder höher) Text und Grafiken aus dem Dokument kopieren oder anderweitig extrahieren durch Vorgänge, die nicht von ExtractContentWithDisabilities gesteuert werden. |
| ModifyTextAnnotations | `20` | Textanmerkungen hinzufügen oder ändern, interaktive Formularfelder ausfüllen und, wenn ModifyContent ebenfalls gesetzt ist, interaktive Formularfelder erstellen oder ändern (einschließlich Signaturfelder). |
| FillForm | `100` | (Sicherheits-Handler der Revision 3 oder höher) Vorhandene interaktive Formularfelder ausfüllen (einschließlich Signaturfelder), selbst wenn ModifyTextAnnotations deaktiviert ist. |
| ExtractContentWithDisabilities | `200` | (Sicherheits-Handler der Revision 3 oder höher) Text und Grafiken extrahieren (zur Unterstützung der Barrierefreiheit für Nutzer mit Behinderungen oder zu anderen Zwecken). |
| AssembleDocument | `400` | (Security handlers der Revision 3 oder höher) Das Dokument zusammenstellen (Seiten einfügen, drehen oder löschen und Lesezeichen oder Miniaturbilder erstellen), selbst wenn ModifyContent gesetzt ist. |
| PrintingQuality | `800` | (Security handlers der Revision 3 oder höher) Das Dokument in eine Darstellung drucken, aus der eine getreue digitale Kopie des PDF-Inhalts erzeugt werden kann. Wenn dieses Bit nicht gesetzt ist (und Bit 3 gesetzt ist), ist das Drucken auf eine niedrigstufige Darstellung des Aussehens beschränkt, möglicherweise von verminderter Qualität. |

### Siehe auch

* namespace [Aspose.Svg.Rendering.Pdf.Encryption](../../aspose.svg.rendering.pdf.encryption/)
* assembly [Aspose.SVG](../../)
