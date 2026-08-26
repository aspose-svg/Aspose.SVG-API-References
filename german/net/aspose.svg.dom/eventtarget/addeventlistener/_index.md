---
title: "EventTarget.AddEventListener"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "EventTarget AddEventListener-Methode. Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel geliefert wird."
type: docs
weight: 20
url: /de/net/aspose.svg.dom/eventtarget/addeventlistener/
---
## AddEventListener(*string, [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/), bool*) {#addeventlistener}

Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird.

Sie funktioniert, indem sie eine Funktion oder ein Objekt, das [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) implementiert, zur Liste der Ereignis-Listener für den angegebenen Ereignistyp auf dem [`EventTarget`](../) hinzufügt, auf dem sie aufgerufen wird. Wenn die Funktion oder das Objekt bereits in der Liste der Ereignis-Listener für dieses Ziel vorhanden ist, wird sie nicht ein zweites Mal hinzugefügt.

```csharp
public void AddEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Der Ereignistyp, für den der Benutzer registriert |
| handler | DOMEventHandler | Nimmt einen [`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/) entgegen, der aufgerufen wird, wenn das Ereignis eintritt. |
| useCapture | Boolean | Wenn true, gibt useCapture an, dass der Benutzer die Erfassung initiieren möchte. Nach dem Initiieren der Erfassung werden alle Ereignisse des angegebenen Typs zuerst an den registrierten [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) gesendet, bevor sie an irgendwelche Event Targets unterhalb von ihnen im Baum gesendet werden. Ereignisse, die im Baum nach oben blubbern, lösen keinen [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) aus, der für die Verwendung von capture vorgesehen ist. |

## Hinweise

Wenn ein [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) zu einem [`EventTarget`](../) hinzugefügt wird, während dieses ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst, kann jedoch in einer späteren Phase des Ereignisflusses, wie der Bubbling‑Phase, ausgelöst werden.

Wenn mehrere identische Event Listener am selben [`EventTarget`](../) mit denselben Parametern registriert werden, werden die doppelten Instanzen verworfen. Sie führen nicht dazu, dass der [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) zweimal aufgerufen wird, und da sie verworfen werden, müssen sie nicht mit der Methode [`RemoveEventListener`](../removeeventlistener/) entfernt werden.

### Siehe auch

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)*) {#addeventlistener_1}

Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird.

Sie funktioniert, indem sie eine Funktion oder ein Objekt, das [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) implementiert, zur Liste der Ereignis-Listener für den angegebenen Ereignistyp auf dem [`EventTarget`](../) hinzufügt, auf dem sie aufgerufen wird. Wenn die Funktion oder das Objekt bereits in der Liste der Ereignis-Listener für dieses Ziel vorhanden ist, wird sie nicht ein zweites Mal hinzugefügt.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Der Ereignistyp, für den der Benutzer registriert |
| Listener | IEventListener | Nimmt ein vom Benutzer implementiertes Interface, das die Methoden enthält, die aufgerufen werden sollen, wenn das Ereignis eintritt. |

## Hinweise

Wenn ein [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) zu einem [`EventTarget`](../) hinzugefügt wird, während dieses ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst, kann jedoch in einer späteren Phase des Ereignisflusses, wie der Bubbling‑Phase, ausgelöst werden.

Wenn mehrere identische Event Listener am selben [`EventTarget`](../) mit denselben Parametern registriert werden, werden die doppelten Instanzen verworfen. Sie führen nicht dazu, dass der [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) zweimal aufgerufen wird, und da sie verworfen werden, müssen sie nicht mit der Methode [`RemoveEventListener`](../removeeventlistener/) entfernt werden.

### Siehe auch

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/), bool*) {#addeventlistener_2}

Richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird.

Sie funktioniert, indem sie eine Funktion oder ein Objekt, das [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) implementiert, zur Liste der Ereignis-Listener für den angegebenen Ereignistyp auf dem [`EventTarget`](../) hinzufügt, auf dem sie aufgerufen wird. Wenn die Funktion oder das Objekt bereits in der Liste der Ereignis-Listener für dieses Ziel vorhanden ist, wird sie nicht ein zweites Mal hinzugefügt.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Der Ereignistyp, für den der Benutzer registriert |
| Listener | IEventListener | Nimmt ein vom Benutzer implementiertes Interface, das die Methoden enthält, die aufgerufen werden sollen, wenn das Ereignis eintritt. |
| useCapture | Boolean | Wenn true, gibt useCapture an, dass der Benutzer die Erfassung initiieren möchte. Nach dem Initiieren der Erfassung werden alle Ereignisse des angegebenen Typs zuerst an den registrierten [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) gesendet, bevor sie an irgendwelche Event Targets unterhalb von ihnen im Baum gesendet werden. Ereignisse, die im Baum nach oben blubbern, lösen keinen [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) aus, der für die Verwendung von capture vorgesehen ist. |

## Hinweise

Wenn ein [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) zu einem [`EventTarget`](../) hinzugefügt wird, während dieses ein Ereignis verarbeitet, wird er nicht durch die aktuellen Aktionen ausgelöst, kann jedoch in einer späteren Phase des Ereignisflusses, wie der Bubbling‑Phase, ausgelöst werden.

Wenn mehrere identische Event Listener am selben [`EventTarget`](../) mit denselben Parametern registriert werden, werden die doppelten Instanzen verworfen. Sie führen nicht dazu, dass der [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) zweimal aufgerufen wird, und da sie verworfen werden, müssen sie nicht mit der Methode [`RemoveEventListener`](../removeeventlistener/) entfernt werden.

### Siehe auch

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
