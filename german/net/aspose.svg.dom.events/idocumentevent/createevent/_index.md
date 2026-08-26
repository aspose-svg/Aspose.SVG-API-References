---
title: "IDocumentEvent.CreateEvent"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "IDocumentEvent CreateEvent‑Methode. Erstellt ein Ereignis eines von der Implementierung unterstützten Typs."
type: docs
weight: 10
url: /de/net/aspose.svg.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Erstellt ein [`Event`](../../event/) eines von der Implementierung unterstützten Typs.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| eventType | String | Der Parameter eventType gibt den Typ des zu erstellenden [`Event`](../../event/)‑Interfaces an. Wenn das angegebene [`Event`](../../event/)‑Interface von der Implementierung unterstützt wird, gibt diese Methode ein neues [`Event`](../../event/) des angeforderten Interface‑Typs zurück. Soll das [`Event`](../../event/) über die Methode [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) gesendet werden, muss nach der Erstellung die entsprechende Methode [`InitEvent`](../../event/initevent/) aufgerufen werden, um die Werte des [`Event`](../../event/) zu initialisieren. |

### Rückgabewert

Das neu erstellte [`Event`](../../event/)

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn die Implementierung den angeforderten Typ des [`Event`](../../event/)‑Interfaces nicht unterstützt |

### Siehe auch

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
