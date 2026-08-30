---
title: "EventTarget.RemoveEventListener"
second_title: "Aspose.SVG för .NET API-referens"
description: "EventTarget RemoveEventListener-metod. Denna metod möjliggör borttagning av händelselyssnare från händelsemålet. Om en IEventListener tas bort från ett EventTarget medan det bearbetar en händelse kommer den inte att utlösas av de pågående åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort"
type: docs
weight: 50
url: /sv/net/aspose.svg.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(*string, [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/), bool*) {#removeeventlistener}

Denna metod tillåter borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) tas bort från ett [`EventTarget`](../) medan den bearbetar en händelse, kommer den inte att triggas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Anger händelsetypen för den [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) som tas bort. |
| handler | DOMEventHandler | Den [`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/) parametern indikerar den [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) som ska tas bort. |
| useCapture | Boolean | Anger om den EventListener som tas bort registrerades som en fångst‑lyssnare eller inte. Om en lyssnare registrerades två gånger, en med fångst och en utan, måste varje tas bort separat. Borttagning av en fångst‑lyssnare påverkar inte en icke‑fångst‑version av samma lyssnare, och vice versa. |

### Se även

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)*) {#removeeventlistener_1}

Denna metod tillåter borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) tas bort från ett [`EventTarget`](../) medan den bearbetar en händelse, kommer den inte att triggas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Anger händelsetypen för den [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) som tas bort. |
| listener | IEventListener | Parametern [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) anger den [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) som ska tas bort. |

### Se även

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/), bool*) {#removeeventlistener_2}

Denna metod tillåter borttagning av händelselyssnare från händelsemålet. Om en [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) tas bort från ett [`EventTarget`](../) medan den bearbetar en händelse, kommer den inte att triggas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Anger händelsetypen för den [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) som tas bort. |
| listener | IEventListener | Parametern [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) anger den [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) som ska tas bort. |
| useCapture | Boolean | Anger om den EventListener som tas bort registrerades som en fångst‑lyssnare eller inte. Om en lyssnare registrerades två gånger, en med fångst och en utan, måste varje tas bort separat. Borttagning av en fångst‑lyssnare påverkar inte en icke‑fångst‑version av samma lyssnare, och vice versa. |

### Se även

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
