---
title: "IEventTarget.RemoveEventListener"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "IEventTarget RemoveEventListener-Methode. Diese Methode ermöglicht das Entfernen von Ereignislistenern vom Ereignisziel. Wenn ein IEventListener von einem EventTarget entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignislistener können nach dem Entfernen niemals aufgerufen werden."
type: docs
weight: 30
url: /de/net/aspose.svg.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(*string, [IEventListener](../../ieventlistener/)*) {#removeeventlistener}

Diese Methode ermöglicht das Entfernen von Ereignislistenern vom Ereignisziel. Wenn ein [`IEventListener`](../../ieventlistener/) von einem [`EventTarget`](../../../aspose.svg.dom/eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignislistener können nach dem Entfernen niemals aufgerufen werden.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Gibt den Ereignistyp des zu entfernenden [`IEventListener`](../../ieventlistener/) an. |
| listener | IEventListener | Der Parameter [`IEventListener`](../../ieventlistener/) gibt den zu entfernenden [`IEventListener`](../../ieventlistener/) an. |

### Siehe auch

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../ieventlistener/), bool*) {#removeeventlistener_1}

Diese Methode ermöglicht das Entfernen von Ereignislistenern vom Ereignisziel. Wenn ein [`IEventListener`](../../ieventlistener/) von einem [`EventTarget`](../../../aspose.svg.dom/eventtarget/) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignislistener können nach dem Entfernen niemals aufgerufen werden.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Gibt den Ereignistyp des zu entfernenden [`IEventListener`](../../ieventlistener/) an. |
| listener | IEventListener | Der Parameter [`IEventListener`](../../ieventlistener/) gibt den zu entfernenden [`IEventListener`](../../ieventlistener/) an. |
| useCapture | Boolean | Gibt an, ob der zu entfernende EventListener als Capturing-Listener registriert war oder nicht. Wenn ein Listener zweimal registriert wurde, einmal mit Capture und einmal ohne, muss jeder separat entfernt werden. Das Entfernen eines Capturing-Listeners beeinflusst nicht die nicht-capturing Version desselben Listeners und umgekehrt. |

### Siehe auch

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
