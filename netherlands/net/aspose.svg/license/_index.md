---
title: "License Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.License klasse. Biedt methoden om het component te licentiëren."
type: docs
weight: 4260
url: /nl/net/aspose.svg/license/
---
## License class

Biedt methoden om het component te licentiëren.

```csharp
public class License
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [License](license/)() | Initialiseert een nieuw exemplaar van deze klasse. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense)(*Stream*) | Licentieert de component. |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense_1)(*string*) | Licentieert de component. |

## Voorbeelden

In dit voorbeeld wordt geprobeerd een licentiebestand met de naam MyLicense.lic te vinden in de map die de component bevat, in de map die de aanroepende assembly bevat, in de map van de entry-assembly en vervolgens in de ingebedde resources van de aanroepende assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

het component‑jar‑bestand:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Zie ook

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
