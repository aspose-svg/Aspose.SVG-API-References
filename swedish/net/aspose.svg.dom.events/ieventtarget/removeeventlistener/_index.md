---
title: "IEventTarget.RemoveEventListener"
second_title: "Aspose.SVG för .NET API-referens"
description: "IEventTarget RemoveEventListener‑metod. Denna metod möjliggör borttagning av händelselyssnare från mål‑händelseobjektet. Om en IEventListener tas bort från ett EventTarget medan det bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort."
type: docs
weight: 30
url: /sv/net/aspose.svg.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(*string, [IEventListener](../../ieventlistener/)*) {#removeeventlistener}

Denna metod möjliggör borttagning av händelselyssnare från mål‑händelsen. Om en [`IEventListener`](../../ieventlistener/) tas bort från ett [`EventTarget`](../../../aspose.svg.dom/eventtarget/) medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Anger händelsetypen för den [`IEventListener`](../../ieventlistener/) som tas bort. |
| listener | IEventListener | Parametern [`IEventListener`](../../ieventlistener/) anger vilken [`IEventListener`](../../ieventlistener/) som ska tas bort. |

### Se även

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../ieventlistener/), bool*) {#removeeventlistener_1}

Denna metod möjliggör borttagning av händelselyssnare från mål‑händelsen. Om en [`IEventListener`](../../ieventlistener/) tas bort från ett [`EventTarget`](../../../aspose.svg.dom/eventtarget/) medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Anger händelsetypen för den [`IEventListener`](../../ieventlistener/) som tas bort. |
| listener | IEventListener | Parametern [`IEventListener`](../../ieventlistener/) anger vilken [`IEventListener`](../../ieventlistener/) som ska tas bort. |
| useCapture | Boolean | Anger om den EventListener som tas bort registrerades som en fångst‑lyssnare eller inte. Om en lyssnare registrerades två gånger, en med fångst och en utan, måste varje tas bort separat. Borttagning av en fångst‑lyssnare påverkar inte en icke‑fångst‑version av samma lyssnare, och vice versa. |

### Se även

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
