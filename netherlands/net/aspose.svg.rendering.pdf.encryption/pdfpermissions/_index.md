---
title: "PdfPermissions‑enum"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Rendering.Pdf.Encryption.PdfPermissions‑enum. Deze enum vertegenwoordigt gebruikersrechten voor een pdf."
type: docs
weight: 5000
url: /nl/net/aspose.svg.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Deze enum vertegenwoordigt de gebruikersrechten voor een pdf.

```csharp
[Flags]
public enum PdfPermissions
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| PrintDocument | `4` | (Beveiligingshandlers van revisie 2) Document afdrukken. (Beveiligingshandlers van revisie 3 of hoger) Document afdrukken (mogelijk niet op het hoogste kwaliteitsniveau, afhankelijk van of PrintingQuality ook is ingesteld). |
| ModifyContent | `8` | De inhoud van het document wijzigen via bewerkingen die niet worden gecontroleerd door ModifyTextAnnotations, FillForm en 11. |
| ExtractContent | `10` | (Beveiligingshandlers van revisie 2) Tekst en grafische elementen uit het document kopiëren of anderszins extraheren, inclusief het extraheren van tekst en grafische elementen (ter ondersteuning van toegankelijkheid voor gebruikers met een beperking of voor andere doeleinden). (Beveiligingshandlers van revisie 3 of hoger) Tekst en grafische elementen uit het document kopiëren of anderszins extraheren via bewerkingen die niet worden gecontroleerd door ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Tekstannotaties toevoegen of wijzigen, interactieve formuliervelden invullen, en, als ModifyContent ook is ingesteld, interactieve formuliervelden maken of wijzigen (inclusief handtekeningvelden). |
| FillForm | `100` | (Beveiligingshandlers van revisie 3 of hoger) Bestaande interactieve formuliervelden invullen (inclusief handtekeningvelden), zelfs als ModifyTextAnnotations is uitgeschakeld. |
| ExtractContentWithDisabilities | `200` | (Beveiligingshandlers van revisie 3 of hoger) Tekst en grafische elementen extraheren (ter ondersteuning van toegankelijkheid voor gebruikers met een beperking of voor andere doeleinden). |
| AssembleDocument | `400` | (Beveiligingshandlers van revisie 3 of hoger) Het document samenstellen (pagina's invoegen, roteren of verwijderen en bladwijzers of miniatuur‑afbeeldingen maken), zelfs als ModifyContent is uitgeschakeld. |
| PrintingQuality | `800` | (Beveiligingshandlers van revisie 3 of hoger) Het document afdrukken naar een weergave waaruit een getrouwe digitale kopie van de PDF‑inhoud kan worden gegenereerd. Wanneer dit bit is uitgeschakeld (en bit 3 is ingesteld), is afdrukken beperkt tot een laag‑niveau weergave van het uiterlijk, mogelijk van verminderde kwaliteit. |

### Zie ook

* namespace [Aspose.Svg.Rendering.Pdf.Encryption](../../aspose.svg.rendering.pdf.encryption/)
* assembly [Aspose.SVG](../../)
