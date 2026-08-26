---
title: "Metered.SetMeteredKey"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Metered SetMeteredKey-Methode. Setzt den öffentlichen und privaten Schlüssel von Metered. Wenn Sie eine Metered-Lizenz beim Start der Anwendung erwerben, sollte diese API normalerweise aufgerufen werden, das ist ausreichend. Falls jedoch immer das Hochladen von Verbrauchsdaten fehlschlägt und 24 Stunden überschritten werden, wird die Lizenz auf den Evaluierungsstatus gesetzt. Um einen solchen Fall zu vermeiden, sollten Sie regelmäßig den Lizenzstatus prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf."
type: docs
weight: 20
url: /de/net/aspose.svg/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Setzt den öffentlichen und privaten Metered‑Schlüssel. Wenn Sie eine Metered‑Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. Sollte jedoch das Hochladen von Verbrauchsdaten ständig fehlschlagen und 24 Stunden überschreiten, wird die Lizenz in den Evaluierungsstatus versetzt. Um diesen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen und bei Evaluierungsstatus diese API erneut aufrufen.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| publicKey | String | öffentlicher Schlüssel |
| privateKey | String | privater Schlüssel |

### Siehe auch

* class [Metered](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
