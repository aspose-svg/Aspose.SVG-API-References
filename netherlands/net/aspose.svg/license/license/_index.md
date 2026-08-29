---
title: "Licentie"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Licentie‑constructor. Initialiseert een nieuwe instantie van deze klasse"
type: docs
weight: 10
url: /nl/net/aspose.svg/license/license/
---
## License constructor

Initialiseert een nieuw exemplaar van deze klasse.

```csharp
public License()
```

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

* class [License](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
