---
title: "Metered‑klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Metered‑klasse. Biedt methoden om de metered‑sleutel in te stellen"
type: docs
weight: 4270
url: /nl/net/aspose.svg/metered/
---
## Metered class

Biedt methoden om een gemeten sleutel in te stellen.

```csharp
public class Metered
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Metered](metered/)() | Initialiseert een nieuw exemplaar van deze klasse. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [SetMeteredKey](../../aspose.svg/metered/setmeteredkey/)(*string, string*) | Stelt de metered openbare en privésleutel in. Als u een metered‑licentie aanschaft, moet deze API worden aangeroepen bij het starten van de applicatie; normaal gesproken is dat voldoende. Als het echter steeds mislukt om verbruiksgegevens te uploaden en de 24 uur overschrijdt, wordt de licentie op evaluatiestatus gezet. Om dit te voorkomen, dient u regelmatig de licentiestatus te controleren; als deze op evaluatiestatus staat, roept u deze API opnieuw aan. |
| static [GetConsumptionCredit](../../aspose.svg/metered/getconsumptioncredit/)() | Haalt verbruikcredit op |
| static [GetConsumptionQuantity](../../aspose.svg/metered/getconsumptionquantity/)() | Haalt verbruikbestandsgrootte op |
| static [IsMeteredLicensed](../../aspose.svg/metered/ismeteredlicensed/)() | Controleer of metered is gelicentieerd |

## Voorbeelden

In dit voorbeeld wordt geprobeerd om de openbare en privésleutel van metered in te stellen

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

het component‑jar‑bestand:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Zie ook

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
