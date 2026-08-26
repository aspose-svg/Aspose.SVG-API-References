---
title: "Metered Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Metered Klasse. Stellt Methoden zum Festlegen des Metered‑Schlüssels bereit"
type: docs
weight: 4270
url: /de/net/aspose.svg/metered/
---
## Metered class

Stellt Methoden zum Festlegen eines gemessenen Schlüssels bereit.

```csharp
public class Metered
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Metered](metered/)() | Initialisiert eine neue Instanz dieser Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetMeteredKey](../../aspose.svg/metered/setmeteredkey/)(*string, string*) | Setzt den öffentlichen und privaten Metered‑Schlüssel. Wenn Sie eine Metered‑Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. Sollte jedoch das Hochladen von Verbrauchsdaten ständig fehlschlagen und 24 Stunden überschreiten, wird die Lizenz in den Evaluierungsstatus versetzt. Um diesen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen und bei Evaluierungsstatus diese API erneut aufrufen. |
| static [GetConsumptionCredit](../../aspose.svg/metered/getconsumptioncredit/)() | Liest das Verbrauchsguthaben |
| static [GetConsumptionQuantity](../../aspose.svg/metered/getconsumptionquantity/)() | Liest die Dateigröße des Verbrauchs |
| static [IsMeteredLicensed](../../aspose.svg/metered/ismeteredlicensed/)() | Prüft, ob Metered lizenziert ist |

## Beispiele

In diesem Beispiel wird versucht, den öffentlichen und privaten Metered‑Schlüssel zu setzen

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

die Komponenten‑Jar‑Datei:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Siehe auch

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
