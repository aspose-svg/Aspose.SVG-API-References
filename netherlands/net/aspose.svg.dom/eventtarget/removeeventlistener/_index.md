---
title: "EventTarget.RemoveEventListener"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "EventTarget RemoveEventListener‑methode. Deze methode maakt het verwijderen van event‑listeners van het event‑target mogelijk. Als een IEventListener wordt verwijderd van een EventTarget terwijl deze een gebeurtenis verwerkt, wordt deze niet geactiveerd door de huidige acties. Event‑listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd"
type: docs
weight: 50
url: /nl/net/aspose.svg.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(*string, [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/), bool*) {#removeeventlistener}

Deze methode maakt het verwijderen van event‑listeners van het event‑target mogelijk. Als een [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een [`EventTarget`](../) terwijl deze een gebeurtenis verwerkt, wordt deze niet geactiveerd door de huidige acties. Event‑listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Specificeert het gebeurtenistype van de te verwijderen [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/). |
| handler | DOMEventHandler | De [`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/)‑parameter geeft de te verwijderen [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) aan. |
| useCapture | Boolean | Specificeert of de te verwijderen EventListener als een capture-listener is geregistreerd of niet. Als een listener twee keer is geregistreerd, één met capture en één zonder, moet elke afzonderlijk worden verwijderd. Het verwijderen van een capture-listener heeft geen invloed op een niet-capture versie van dezelfde listener, en omgekeerd. |

### Zie ook

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)*) {#removeeventlistener_1}

Deze methode maakt het verwijderen van event‑listeners van het event‑target mogelijk. Als een [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een [`EventTarget`](../) terwijl deze een gebeurtenis verwerkt, wordt deze niet geactiveerd door de huidige acties. Event‑listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Specificeert het gebeurtenistype van de te verwijderen [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/). |
| listener | IEventListener | De [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) parameter geeft de [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) aan die verwijderd moet worden. |

### Zie ook

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/), bool*) {#removeeventlistener_2}

Deze methode maakt het verwijderen van event‑listeners van het event‑target mogelijk. Als een [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een [`EventTarget`](../) terwijl deze een gebeurtenis verwerkt, wordt deze niet geactiveerd door de huidige acties. Event‑listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Specificeert het gebeurtenistype van de te verwijderen [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/). |
| listener | IEventListener | De [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) parameter geeft de [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) aan die verwijderd moet worden. |
| useCapture | Boolean | Specificeert of de te verwijderen EventListener als een capture-listener is geregistreerd of niet. Als een listener twee keer is geregistreerd, één met capture en één zonder, moet elke afzonderlijk worden verwijderd. Het verwijderen van een capture-listener heeft geen invloed op een niet-capture versie van dezelfde listener, en omgekeerd. |

### Zie ook

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
