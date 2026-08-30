---
title: "EventTarget.DispatchEvent"
second_title: "Aspose.SVG för .NET API-referens"
description: "EventTarget DispatchEvent-metoden. Skickar en händelse till det angivna IEventTarget synkront och anropar de påverkade EventListeners i rätt ordning. De normala händelsebehandlingsreglerna, inklusive fångst- och valfri bubbelfas, gäller också för händelser som skickas manuellt med DispatchEvent."
type: docs
weight: 30
url: /sv/net/aspose.svg.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Skickar en händelse till det angivna [`IEventTarget`](../../../aspose.svg.dom.events/ieventtarget/), (synkront) och anropar de påverkade EventListeners i rätt ordning. De normala händelsebehandlingsreglerna (inklusive fångst- och valfri bubbelfas) gäller också för händelser som skickas manuellt med [`DispatchEvent`](../../../aspose.svg.dom.events/ieventtarget/dispatchevent/).

```csharp
public bool DispatchEvent(Event @event)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| händelse | Händelse | Anger händelsetypen, beteendet och kontextuell information som ska användas vid bearbetning av händelsen. |

### Returvärde

Returvärdet för `DispatchEvent` indikerar om någon av lyssnarna som hanterade händelsen anropade [`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault/). Om [`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault/) anropades är värdet falskt, annars är värdet sant.

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../domexception/) |  |

## Anmärkningar

Händelser som skickas på detta sätt kommer att ha samma fångst- och bubbelbeteende som händelser som skickas direkt av implementationen. Målet för händelsen är det [`EventTarget`](../) på vilket `DispatchEvent` anropas.

### Se även

* class [Event](../../../aspose.svg.dom.events/event/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
