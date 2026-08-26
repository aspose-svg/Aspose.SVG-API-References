---
title: "SVGSVGElement.CreateEvent"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGSVGElement CreateEvent‑Methode. Erstellt ein Event eines von der Implementierung unterstützten Typs."
type: docs
weight: 110
url: /de/net/aspose.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Erstellt ein [`Event`](../../../aspose.svg.dom.events/event/) eines von der Implementierung unterstützten Typs.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| eventType | String | Der Parameter eventType gibt den Typ der zu erstellenden [`Event`](../../../aspose.svg.dom.events/event/)‑Schnittstelle an. Wenn die angegebene [`Event`](../../../aspose.svg.dom.events/event/)‑Schnittstelle von der Implementierung unterstützt wird, gibt diese Methode ein neues [`Event`](../../../aspose.svg.dom.events/event/) des angeforderten Schnittstellentyps zurück. Wenn das [`Event`](../../../aspose.svg.dom.events/event/) über die Methode [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) gesendet werden soll, muss nach der Erstellung die entsprechende Methode [`InitEvent`](../../../aspose.svg.dom.events/event/initevent/) aufgerufen werden, um die Werte des [`Event`](../../../aspose.svg.dom.events/event/) zu initialisieren. |

### Rückgabewert

Das neu erstellte [`Event`](../../../aspose.svg.dom.events/event/)

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn die Implementierung den angeforderten Typ der [`Event`](../../../aspose.svg.dom.events/event/) Schnittstelle nicht unterstützt |

### Siehe auch

* class [Event](../../../aspose.svg.dom.events/event/)
* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
