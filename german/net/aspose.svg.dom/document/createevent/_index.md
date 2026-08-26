---
title: "Document.CreateEvent"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Document CreateEvent Methode. Erstellt ein Event eines von der Implementierung unterstützten Typs"
type: docs
weight: 880
url: /de/net/aspose.svg.dom/document/createevent/
---
## Document.CreateEvent method

Erstellt ein [`Event`](../../../aspose.svg.dom.events/event/) eines von der Implementierung unterstützten Typs.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| eventType | String | Der Parameter eventType gibt den Typ der zu erstellenden [`Event`](../../../aspose.svg.dom.events/event/) Schnittstelle an. Wenn die angegebene [`Event`](../../../aspose.svg.dom.events/event/) Schnittstelle von der Implementierung unterstützt wird, gibt diese Methode ein neues [`Event`](../../../aspose.svg.dom.events/event/) des angeforderten Schnittstellentyps zurück. Wenn das [`Event`](../../../aspose.svg.dom.events/event/) über die Methode [`DispatchEvent`](../../../aspose.svg.dom.events/ieventtarget/dispatchevent/) gesendet werden soll, muss nach der Erstellung die entsprechende Methode [`InitEvent`](../../../aspose.svg.dom.events/event/initevent/) aufgerufen werden, um die Werte des [`Event`](../../../aspose.svg.dom.events/event/) zu initialisieren. |

### Rückgabewert

Das neu erstellte [`Event`](../../../aspose.svg.dom.events/event/)

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn die Implementierung den angeforderten Typ der [`Event`](../../../aspose.svg.dom.events/event/) Schnittstelle nicht unterstützt |

### Siehe auch

* class [Event](../../../aspose.svg.dom.events/event/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
