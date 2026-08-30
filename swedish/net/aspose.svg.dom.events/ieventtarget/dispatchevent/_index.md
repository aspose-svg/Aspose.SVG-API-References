---
title: "IEventTarget.DispatchEvent"
second_title: "Aspose.SVG för .NET API-referens"
description: "IEventTarget DispatchEvent‑metod. Denna metod möjliggör utskick av händelser till implementationens händelsemodell."
type: docs
weight: 20
url: /sv/net/aspose.svg.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Denna metod möjliggör sändning av händelser till implementationens händelsemodell.

```csharp
public bool DispatchEvent(Event @event)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| händelse | Händelse | Anger händelsetypen, beteendet och kontextuell information som ska användas vid bearbetning av händelsen. |

### Returvärde

Returvärdet för [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) indikerar om någon av lyssnarna som hanterade händelsen anropade [`PreventDefault`](../../event/preventdefault/). Om [`PreventDefault`](../../event/preventdefault/) anropades är värdet falskt, annars är värdet sant.

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) |  |

## Anmärkningar

Händelser som skickas på detta sätt kommer att ha samma fångst‑ och bubbla‑beteende som händelser som skickas direkt av implementationen. Målet för händelsen är det [`EventTarget`](../../../aspose.svg.dom/eventtarget/) på vilket [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) anropas.

### Se även

* class [Event](../../event/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
