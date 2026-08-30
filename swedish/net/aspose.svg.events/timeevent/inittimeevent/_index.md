---
title: "TimeEvent.InitTimeEvent"
second_title: "Aspose.SVG för .NET API-referens"
description: "TimeEvent InitTimeEvent-metod. Metoden initTimeEvent används för att initiera värdet för ett TimeEvent som skapats via DocumentEvent-gränssnittet. Denna metod får endast anropas innan TimeEvent har skickats via dispatchEvent-metoden, men den kan anropas flera gånger under den fasen om det behövs. Om den anropas flera gånger har det sista anropet företräde."
type: docs
weight: 30
url: /sv/net/aspose.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

Metoden initTimeEvent används för att initiera värdet av ett TimeEvent skapat via DocumentEvent‑gränssnittet. Denna metod får endast anropas innan TimeEvent har skickats via dispatchEvent‑metoden, men den kan anropas flera gånger under den fasen om så behövs. Om den anropas flera gånger har det sista anropet företräde.

```csharp
public void InitTimeEvent(string typeArg, IAbstractView viewArg, long detailArg)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typeArg | String | Anger händelsetypen. |
| viewArg | IAbstractView | Anger händelsens AbstractView. |
| detailArg | Int64 | Anger händelsens detalj. |

### Se även

* interface [IAbstractView](../../../aspose.svg.dom.views/iabstractview/)
* class [TimeEvent](../)
* namespace [Aspose.Svg.Events](../../../aspose.svg.events/)
* assembly [Aspose.SVG](../../../)
