---
title: IEventTarget.RemoveEventListener
second_title: Aspose.SVG für .NET-API-Referenz
description: IEventTarget methode. Diese Methode ermöglicht das Entfernen von EreignisListenern aus dem Ereignisziel. Wenn anIEventListener wird aus einem entferntEventTarget während es ein Ereignis verarbeitet wird es nicht durch die aktuellen Aktionen ausgelöst. EreignisListener können nie aufgerufen werden nachdem sie entfernt wurden.
type: docs
weight: 30
url: /de/net/aspose.svg.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(string, IEventListener) {#removeeventlistener}

Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../ieventlistener/) wird aus einem entfernt[`EventTarget`](../../../aspose.svg.dom/eventtarget/) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Gibt den Ereignistyp der an[`IEventListener`](../../ieventlistener/) entfernt werden. |
| listener | IEventListener | Der[`IEventListener`](../../ieventlistener/) Parameter gibt die an[`IEventListener`](../../ieventlistener/) entfernt werden. |

### Siehe auch

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namensraum [Aspose.Svg.Dom.Events](../../ieventtarget/)
* Montage [Aspose.SVG](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_1}

Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../ieventlistener/) wird aus einem entfernt[`EventTarget`](../../../aspose.svg.dom/eventtarget/) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Gibt den Ereignistyp der an[`IEventListener`](../../ieventlistener/) entfernt werden. |
| listener | IEventListener | Der[`IEventListener`](../../ieventlistener/) Parameter gibt die an[`IEventListener`](../../ieventlistener/) entfernt werden. |
| useCapture | Boolean | Gibt an, ob der zu entfernende EventListener als erfassender Listener registriert wurde oder nicht. Wenn ein Listener zweimal registriert wurde, einer mit Erfassung und einer ohne, muss jeder separat entfernt werden. Das Entfernen eines erfassenden Listeners wirkt sich nicht auf eine nicht erfassende Version aus desselben Zuhörers und umgekehrt. |

### Siehe auch

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namensraum [Aspose.Svg.Dom.Events](../../ieventtarget/)
* Montage [Aspose.SVG](../../../)


