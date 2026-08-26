---
title: "EventTarget.DispatchEvent"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "EventTarget DispatchEvent-Methode. Sendet ein Ereignis an das angegebene IEventTarget synchron und ruft die betroffenen EventListener in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln, einschließlich der Erfassungs- und optionalen Bubbling-Phase, gelten ebenfalls für Ereignisse, die manuell mit DispatchEvent gesendet werden."
type: docs
weight: 30
url: /de/net/aspose.svg.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Sendet ein Ereignis an das angegebene [`IEventTarget`](../../../aspose.svg.dom.events/ieventtarget/), (synchron) und ruft die betroffenen EventListener in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln (einschließlich der Erfassungs- und optionalen Bubbling-Phase) gelten ebenfalls für Ereignisse, die manuell mit [`DispatchEvent`](../../../aspose.svg.dom.events/ieventtarget/dispatchevent/) gesendet werden.

```csharp
public bool DispatchEvent(Event @event)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| event | Ereignis | Gibt den Ereignistyp, das Verhalten und die kontextbezogenen Informationen an, die bei der Verarbeitung des Ereignisses verwendet werden sollen. |

### Rückgabewert

Der Rückgabewert von `DispatchEvent` gibt an, ob einer der Listener, die das Ereignis verarbeitet haben, [`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault/) aufgerufen hat. Wenn [`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault/) aufgerufen wurde, ist der Wert false, andernfalls ist er true.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../domexception/) |  |

## Hinweise

Auf diese Weise gesendete Ereignisse haben dasselbe Erfassungs- und Bubbling-Verhalten wie Ereignisse, die direkt von der Implementierung gesendet werden. Das Ziel des Ereignisses ist das [`EventTarget`](../), auf dem `DispatchEvent` aufgerufen wird.

### Siehe auch

* class [Event](../../../aspose.svg.dom.events/event/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
