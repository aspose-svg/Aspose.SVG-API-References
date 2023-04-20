---
title: Class Metered
second_title: Aspose.SVG für .NET-API-Referenz
description: Aspose.Svg.Metered klas. Bietet Methoden zum Festlegen von gemessenen Schlüsseln.
type: docs
weight: 2200
url: /de/net/aspose.svg/metered/
---
## Metered class

Bietet Methoden zum Festlegen von gemessenen Schlüsseln.

```csharp
public class Metered
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Metered](metered/)() | Initialisiert eine neue Instanz dieser Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetMeteredKey](../../aspose.svg/metered/setmeteredkey/)(string, string) | Legt den gemessenen öffentlichen und privaten Schlüssel fest. Wenn Sie eine gemessene Lizenz erwerben, sollte beim Start der Anwendung diese API aufgerufen werden, normalerweise reicht dies aus. Wenn es jedoch immer fehlschlägt, Verbrauchsdaten hochzuladen und 24 Stunden überschreiten, wird die Lizenz auf den Evaluierungsstatus gesetzt, um einen solchen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig überprüfen. Wenn es sich um einen Evaluierungsstatus handelt, rufen Sie diese API erneut auf. |
| static [GetConsumptionCredit](../../aspose.svg/metered/getconsumptioncredit/)() | erhält Verbrauchsguthaben |
| static [GetConsumptionQuantity](../../aspose.svg/metered/getconsumptionquantity/)() | Ruft die Verbrauchsdateigröße ab |

### Beispiele

In diesem Beispiel wird versucht, einen getakteten öffentlichen und privaten Schlüssel festzulegen

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

die Komponenten-JAR-Datei:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Siehe auch

* namensraum [Aspose.Svg](../../aspose.svg/)
* Montage [Aspose.SVG](../../)


