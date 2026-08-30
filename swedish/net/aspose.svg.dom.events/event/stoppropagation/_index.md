---
title: "Event.StopPropagation"
second_title: "Aspose.SVG för .NET API-referens"
description: "Event StopPropagation‑metod. StopPropagation‑metoden används för att förhindra vidare spridning av ett event under händelseflödet."
type: docs
weight: 140
url: /sv/net/aspose.svg.dom.events/event/stoppropagation/
---
## Event.StopPropagation method

Metoden `StopPropagation` används för att förhindra vidare spridning av ett event under händelseflödet.

```csharp
public void StopPropagation()
```

## Anmärkningar

Om den här metoden anropas av någon [`IEventListener`](../../ieventlistener/) kommer händelsen att sluta spridas genom trädet. Händelsen kommer att slutföra utskick till alla lyssnare på den aktuella [`IEventTarget`](../../ieventtarget/) innan händelseflödet stoppas. Denna metod kan användas under vilken fas som helst av händelseflödet.

### Se även

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
