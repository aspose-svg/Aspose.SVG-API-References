---
title: "Event.InitEvent"
second_title: "Aspose.SVG för .NET API-referens"
description: "Event InitEvent‑metod. InitEvent‑metoden används för att initiera värdet av ett Event som skapats genom IDocumentEvent‑gränssnittet"
type: docs
weight: 110
url: /sv/net/aspose.svg.dom.events/event/initevent/
---
## Event.InitEvent method

Metoden `InitEvent` används för att initiera värdet av ett [`Event`](../) som skapats genom [`IDocumentEvent`](../../idocumentevent/)‑gränssnittet.

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Händelsetypen. |
| bubbles | Boolean | om den är satt till `true` [bubbles]. |
| cancelable | Boolean | om den är satt till `true` [cancelable]. |

## Anmärkningar

Denna metod får endast anropas innan Event har dispatchats via metoden [`DispatchEvent`](../../ieventtarget/dispatchevent/), men den kan anropas flera gånger under den fasen om det behövs. Om den anropas flera gånger har det sista anropet företräde. Om den anropas från en subklass av Event‑gränssnittet modifieras endast de värden som anges i initEvent‑metoden, alla andra attribut lämnas oförändrade.

### Se även

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
