---
title: "EventTarget.RemoveEventListener"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "EventTarget RemoveEventListener-Methode. Diese Methode ermöglicht das Entfernen von Ereignis-Listenern vom Ereignisziel. Wenn ein IEventListener von einem EventTarget entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nach dem Entfernen niemals aufgerufen werden."
type: docs
weight: 50
url: /de/net/aspose.svg.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(*string, [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/), bool*) {#removeeventlistener}

Diese Methode ermöglicht das Entfernen von Ereignis-Listenern vom Ereignisziel. Wenn ein [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) von einem [`EventTarget`](../) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nach dem Entfernen niemals aufgerufen werden.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Gibt den Ereignistyp des zu entfernenden [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) an. |
| handler | DOMEventHandler | Der Parameter [`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/) gibt den zu entfernenden [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) an. |
| useCapture | Boolean | Gibt an, ob der zu entfernende EventListener als Capturing-Listener registriert war oder nicht. Wenn ein Listener zweimal registriert wurde, einmal mit Capture und einmal ohne, muss jeder separat entfernt werden. Das Entfernen eines Capturing-Listeners beeinflusst nicht die nicht-capturing Version desselben Listeners und umgekehrt. |

### Siehe auch

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)*) {#removeeventlistener_1}

Diese Methode ermöglicht das Entfernen von Ereignis-Listenern vom Ereignisziel. Wenn ein [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) von einem [`EventTarget`](../) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nach dem Entfernen niemals aufgerufen werden.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Gibt den Ereignistyp des zu entfernenden [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) an. |
| listener | IEventListener | Der [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) Parameter gibt an, welcher [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) entfernt werden soll. |

### Siehe auch

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/), bool*) {#removeeventlistener_2}

Diese Methode ermöglicht das Entfernen von Ereignis-Listenern vom Ereignisziel. Wenn ein [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) von einem [`EventTarget`](../) entfernt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nach dem Entfernen niemals aufgerufen werden.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Gibt den Ereignistyp des zu entfernenden [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) an. |
| listener | IEventListener | Der [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) Parameter gibt an, welcher [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) entfernt werden soll. |
| useCapture | Boolean | Gibt an, ob der zu entfernende EventListener als Capturing-Listener registriert war oder nicht. Wenn ein Listener zweimal registriert wurde, einmal mit Capture und einmal ohne, muss jeder separat entfernt werden. Das Entfernen eines Capturing-Listeners beeinflusst nicht die nicht-capturing Version desselben Listeners und umgekehrt. |

### Siehe auch

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
