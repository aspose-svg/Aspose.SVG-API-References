---
title: "License-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.License-klass. Tillhandahåller metoder för att licensiera komponenten."
type: docs
weight: 4260
url: /sv/net/aspose.svg/license/
---
## License class

Tillhandahåller metoder för att licensiera komponenten.

```csharp
public class License
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [License](license/)() | Initierar en ny instans av denna klass. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense)(*Stream*) | Licensierar komponenten. |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense_1)(*string*) | Licensierar komponenten. |

## Exempel

I det här exemplet kommer ett försök att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande sammansättningen, i mappen för startsammanställningen och sedan i de inbäddade resurserna för den anropande sammansättningen.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

komponent‑jar‑filen:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Se även

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
