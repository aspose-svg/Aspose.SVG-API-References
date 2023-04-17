---
title: Event.PreventDefault
second_title: Aspose.SVG für .NET-API-Referenz
description: Event methode. Wenn eine Veranstaltung stornierbar ist wird diePreventDefault Methode wird verwendet um anzugeben dass das Ereignis abgebrochen werden soll  was bedeutet dass eine Standardaktion die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt wird nicht ausgeführt wird.
type: docs
weight: 120
url: /de/net/aspose.svg.dom.events/event/preventdefault/
---
## Event.PreventDefault method

Wenn eine Veranstaltung stornierbar ist, wird die`PreventDefault` -Methode wird verwendet, um anzugeben, dass das Ereignis abgebrochen werden soll, , was bedeutet, dass eine Standardaktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt wird, nicht ausgeführt wird.

```csharp
public void PreventDefault()
```

### Bemerkungen

Wenn während irgendeiner Phase des Ereignisflusses die`PreventDefault`Methode aufgerufen wird, wird das Ereignis abgebrochen. Jede mit dem Ereignis verbundene Standardaktion wird nicht ausgeführt. Der Aufruf dieser Methode für ein nicht stornierbares Ereignis hat keine Wirkung. Einmal`PreventDefault` aufgerufen wurde, bleibt es während der restlichen Ausbreitung des Ereignisses in Kraft. Diese Methode kann in jeder Phase des Ereignisablaufs verwendet werden.

### Siehe auch

* class [Event](../)
* namensraum [Aspose.Svg.Dom.Events](../../event/)
* Montage [Aspose.SVG](../../../)


