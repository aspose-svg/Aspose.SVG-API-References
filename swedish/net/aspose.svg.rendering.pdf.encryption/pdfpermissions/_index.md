---
title: "PdfPermissions‑enum"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Rendering.Pdf.Encryption.PdfPermissions enum. Denna enum representerar användarbehörigheter för en pdf."
type: docs
weight: 5000
url: /sv/net/aspose.svg.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Denna enum representerar användarens behörigheter för en pdf.

```csharp
[Flags]
public enum PdfPermissions
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| PrintDocument | `4` | (Säkerhetshanterare för revision 2) Skriv ut dokumentet. (Säkerhetshanterare för revision 3 eller högre) Skriv ut dokumentet (möjligen inte på högsta kvalitet, beroende på om PrintingQuality också är inställd). |
| ModifyContent | `8` | Ändra dokumentets innehåll genom operationer som inte styrs av ModifyTextAnnotations, FillForm och 11. |
| ExtractContent | `10` | (Säkerhetshanterare för revision 2) Kopiera eller på annat sätt extrahera text och grafik från dokumentet, inklusive extrahering av text och grafik (för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål). (Säkerhetshanterare för revision 3 eller högre) Kopiera eller på annat sätt extrahera text och grafik från dokumentet genom operationer som inte styrs av ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Lägg till eller ändra textanteckningar, fyll i interaktiva formulärfält och, om ModifyContent också är inställt, skapa eller ändra interaktiva formulärfält (inklusive signaturfält). |
| FillForm | `100` | (Säkerhetshanterare för revision 3 eller högre) Fyll i befintliga interaktiva formulärfält (inklusive signaturfält), även om ModifyTextAnnotations är avstängt. |
| ExtractContentWithDisabilities | `200` | (Säkerhetshanterare för revision 3 eller högre) Extrahera text och grafik (för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål). |
| AssembleDocument | `400` | (Säkerhetshanterare för revision 3 eller högre) Sätt ihop dokumentet (infoga, rotera eller ta bort sidor samt skapa bokmärken eller miniatyrbilder), även om ModifyContent är avstängt. |
| PrintingQuality | `800` | (Säkerhetshanterare för revision 3 eller högre) Skriv ut dokumentet till en representation från vilken en exakt digital kopia av PDF‑innehållet kan genereras. När denna bit är avstängd (och bit 3 är på), begränsas utskriften till en låg‑nivå representation av utseendet, möjligen med försämrad kvalitet. |

### Se även

* namespace [Aspose.Svg.Rendering.Pdf.Encryption](../../aspose.svg.rendering.pdf.encryption/)
* assembly [Aspose.SVG](../../)
