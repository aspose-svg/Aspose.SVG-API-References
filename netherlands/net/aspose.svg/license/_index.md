---
title: Class License
second_title: Aspose.SVG voor .NET API-referentie
description: Aspose.Svg.License klas. Biedt methoden om de component te licentiëren.
type: docs
weight: 2190
url: /nl/net/aspose.svg/license/
---
## License class

Biedt methoden om de component te licentiëren.

```csharp
public class License
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [License](license/)() | Initialiseert een nieuwe instantie van deze klasse. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense)(Stream) | Licentie voor de component. |
| [SetLicense](../../aspose.svg/license/setlicense/#setlicense_1)(string) | Licentie voor de component. |

### Voorbeelden

In dit voorbeeld wordt geprobeerd een licentiebestand met de naam MyLicense.lic te vinden in de map die bevat de component, in de map die de aanroepende assembly bevat, in de map van de entry-assembly en vervolgens in de ingebedde bronnen van de aanroepende assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

het component jar-bestand:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Zie ook

* naamruimte [Aspose.Svg](../../aspose.svg/)
* montage [Aspose.SVG](../../)


