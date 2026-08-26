---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "IEventTarget AddEventListener-Methode. Diese Methode ermöglicht die Registrierung von Ereignislistenern am Ereignisziel."
type: docs
weight: 10
url: /de/net/aspose.svg.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(*string, [IEventListener](../../ieventlistener/)*) {#addeventlistener}

Diese Methode ermöglicht die Registrierung von Event‑Listenern auf dem Ereignisziel.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Der Ereignistyp, für den der Benutzer registriert |
| Listener | IEventListener | Nimmt ein vom Benutzer implementiertes Interface, das die Methoden enthält, die aufgerufen werden sollen, wenn das Ereignis eintritt. |

## Hinweise

Wenn ein [`IEventListener`](../../ieventlistener/) zu einem [`EventTarget`](../../../aspose.svg.dom/eventtarget/) hinzugefügt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst, kann jedoch in einer späteren Phase des Ereignisflusses, wie der Bubbling‑Phase, ausgelöst werden.

Wenn mehrere identische Event‑Listener am selben [`EventTarget`](../../../aspose.svg.dom/eventtarget/) mit denselben Parametern registriert werden, werden die doppelten Instanzen verworfen. Sie führen nicht dazu, dass der [`IEventListener`](../../ieventlistener/) zweimal aufgerufen wird, und da sie verworfen werden, müssen sie nicht mit der Methode [`RemoveEventListener`](../removeeventlistener/) entfernt werden.

### Siehe auch

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../ieventlistener/), bool*) {#addeventlistener_1}

Diese Methode ermöglicht die Registrierung von Event‑Listenern auf dem Ereignisziel.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Der Ereignistyp, für den der Benutzer registriert |
| Listener | IEventListener | Nimmt ein vom Benutzer implementiertes Interface, das die Methoden enthält, die aufgerufen werden sollen, wenn das Ereignis eintritt. |
| useCapture | Boolean | Wenn true, gibt useCapture an, dass der Benutzer die Erfassung initiieren möchte. Nach dem Initiieren der Erfassung werden alle Ereignisse des angegebenen Typs zuerst an den registrierten [`IEventListener`](../../ieventlistener/) gesendet, bevor sie an irgendwelche darunter liegenden Event‑Targets im Baum gesendet werden. Ereignisse, die im Baum nach oben blubbern, lösen keinen für die Erfassung vorgesehenen [`IEventListener`](../../ieventlistener/) aus. |

## Hinweise

Wenn ein [`IEventListener`](../../ieventlistener/) zu einem [`EventTarget`](../../../aspose.svg.dom/eventtarget/) hinzugefügt wird, während es ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst, kann jedoch in einer späteren Phase des Ereignisflusses, wie der Bubbling‑Phase, ausgelöst werden.

Wenn mehrere identische Event‑Listener am selben [`EventTarget`](../../../aspose.svg.dom/eventtarget/) mit denselben Parametern registriert werden, werden die doppelten Instanzen verworfen. Sie führen nicht dazu, dass der [`IEventListener`](../../ieventlistener/) zweimal aufgerufen wird, und da sie verworfen werden, müssen sie nicht mit der Methode [`RemoveEventListener`](../removeeventlistener/) entfernt werden.

### Siehe auch

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
