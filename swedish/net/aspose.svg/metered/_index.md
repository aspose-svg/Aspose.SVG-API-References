---
title: "Metered-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Metered-klass. Tillhandahåller metoder för att ställa in metered-nyckel"
type: docs
weight: 4270
url: /sv/net/aspose.svg/metered/
---
## Metered class

Tillhandahåller metoder för att ange mätad nyckel.

```csharp
public class Metered
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Metered](metered/)() | Initierar en ny instans av denna klass. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [SetMeteredKey](../../aspose.svg/metered/setmeteredkey/)(*string, string*) | Ställer in metered offentlig och privat nyckel. Om du köper en metered-licens, bör detta API anropas när applikationen startas; normalt räcker det. Men om uppladdning av förbrukningsdata ständigt misslyckas och överstiger 24 timmar, kommer licensen att sättas till utvärderingsstatus. För att undvika detta bör du regelbundet kontrollera licensstatusen; om den är i utvärderingsstatus, anropa detta API igen. |
| static [GetConsumptionCredit](../../aspose.svg/metered/getconsumptioncredit/)() | Hämtar förbrukningskredit |
| static [GetConsumptionQuantity](../../aspose.svg/metered/getconsumptionquantity/)() | Hämtar förbrukningsfilens storlek |
| static [IsMeteredLicensed](../../aspose.svg/metered/ismeteredlicensed/)() | Kontrollera om metered är licensierad |

## Exempel

I detta exempel kommer ett försök att göras att ställa in metered offentlig och privat nyckel

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

komponent‑jar‑filen:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Se även

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
