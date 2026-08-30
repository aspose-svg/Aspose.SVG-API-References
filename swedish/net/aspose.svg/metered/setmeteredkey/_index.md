---
title: "Metered.SetMeteredKey"
second_title: "Aspose.SVG för .NET API-referens"
description: "Metered SetMeteredKey metod. Ställer in metered offentliga och privata nycklar. Om du köper en metered-licens när du startar applikationen bör detta API normalt anropas, det räcker. Men om uppladdning av konsumtionsdata alltid misslyckas och överstiger 24 timmar kommer licensen att sättas till utvärderingsstatus; för att undvika detta bör du regelbundet kontrollera licensstatusen och om den är i utvärderingsstatus anropa detta API igen."
type: docs
weight: 20
url: /sv/net/aspose.svg/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Ställer in metered offentlig och privat nyckel. Om du köper en metered-licens, bör detta API anropas när applikationen startas; normalt räcker det. Men om uppladdning av förbrukningsdata ständigt misslyckas och överstiger 24 timmar, kommer licensen att sättas till utvärderingsstatus. För att undvika detta bör du regelbundet kontrollera licensstatusen; om den är i utvärderingsstatus, anropa detta API igen.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicKey | String | offentlig nyckel |
| privateKey | String | privat nyckel |

### Se även

* class [Metered](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
