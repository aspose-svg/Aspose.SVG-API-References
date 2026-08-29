---
title: "TimeEvent.InitTimeEvent"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "TimeEvent InitTimeEvent-methode. De initTimeEvent-methode wordt gebruikt om de waarde van een TimeEvent te initialiseren die via de DocumentEvent-interface is gemaakt. Deze methode mag alleen worden aangeroepen voordat de TimeEvent is verzonden via de dispatchEvent-methode, hoewel hij tijdens die fase indien nodig meerdere keren kan worden aangeroepen. Als hij meerdere keren wordt aangeroepen, heeft de laatste aanroep voorrang."
type: docs
weight: 30
url: /nl/net/aspose.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

De initTimeEvent‑methode wordt gebruikt om de waarde van een TimeEvent te initialiseren die via de DocumentEvent‑interface is gemaakt. Deze methode mag alleen worden aangeroepen voordat de TimeEvent is verzonden via de dispatchEvent‑methode, hoewel hij indien nodig meerdere keren tijdens die fase kan worden aangeroepen. Als hij meerdere keren wordt aangeroepen, heeft de laatste aanroep voorrang.

```csharp
public void InitTimeEvent(string typeArg, IAbstractView viewArg, long detailArg)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeArg | String | Specificeert het type van het evenement. |
| viewArg | IAbstractView | Specificeert de AbstractView van het evenement. |
| detailArg | Int64 | Specificeert de detailinformatie van het evenement. |

### Zie ook

* interface [IAbstractView](../../../aspose.svg.dom.views/iabstractview/)
* class [TimeEvent](../)
* namespace [Aspose.Svg.Events](../../../aspose.svg.events/)
* assembly [Aspose.SVG](../../../)
