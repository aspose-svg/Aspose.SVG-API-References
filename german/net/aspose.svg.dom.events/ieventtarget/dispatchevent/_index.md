---
title: "IEventTarget.DispatchEvent"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "IEventTarget DispatchEvent-Methode. Diese Methode ermöglicht das Senden von Ereignissen in das Ereignismodell der Implementierung."
type: docs
weight: 20
url: /de/net/aspose.svg.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Diese Methode ermöglicht das Senden von Ereignissen in das Ereignismodell der Implementierung.

```csharp
public bool DispatchEvent(Event @event)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| event | Ereignis | Gibt den Ereignistyp, das Verhalten und die kontextbezogenen Informationen an, die bei der Verarbeitung des Ereignisses verwendet werden sollen. |

### Rückgabewert

Der Rückgabewert von [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) gibt an, ob einer der Listener, die das Ereignis verarbeitet haben, [`PreventDefault`](../../event/preventdefault/) aufgerufen hat. Wenn [`PreventDefault`](../../event/preventdefault/) aufgerufen wurde, ist der Wert false, andernfalls ist er true.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) |  |

## Hinweise

Auf diese Weise gesendete Ereignisse haben das gleiche Capturing- und Bubbling-Verhalten wie Ereignisse, die direkt von der Implementierung gesendet werden. Das Ziel des Ereignisses ist das [`EventTarget`](../../../aspose.svg.dom/eventtarget/), auf dem [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) aufgerufen wird.

### Siehe auch

* class [Event](../../event/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
