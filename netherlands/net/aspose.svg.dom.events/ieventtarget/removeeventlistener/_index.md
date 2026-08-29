---
title: "IEventTarget.RemoveEventListener"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "IEventTarget RemoveEventListener-methode. Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een IEventListener wordt verwijderd van een EventTarget terwijl deze een gebeurtenis verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd."
type: docs
weight: 30
url: /nl/net/aspose.svg.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(*string, [IEventListener](../../ieventlistener/)*) {#removeeventlistener}

Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een [`IEventListener`](../../ieventlistener/) wordt verwijderd van een [`EventTarget`](../../../aspose.svg.dom/eventtarget/) terwijl deze een gebeurtenis verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Specificeert het gebeurtenistype van de te verwijderen [`IEventListener`](../../ieventlistener/). |
| listener | IEventListener | De [`IEventListener`](../../ieventlistener/) parameter geeft de te verwijderen [`IEventListener`](../../ieventlistener/) aan. |

### Zie ook

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../ieventlistener/), bool*) {#removeeventlistener_1}

Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een [`IEventListener`](../../ieventlistener/) wordt verwijderd van een [`EventTarget`](../../../aspose.svg.dom/eventtarget/) terwijl deze een gebeurtenis verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Specificeert het gebeurtenistype van de te verwijderen [`IEventListener`](../../ieventlistener/). |
| listener | IEventListener | De [`IEventListener`](../../ieventlistener/) parameter geeft de te verwijderen [`IEventListener`](../../ieventlistener/) aan. |
| useCapture | Boolean | Specificeert of de te verwijderen EventListener als een capture-listener is geregistreerd of niet. Als een listener twee keer is geregistreerd, één met capture en één zonder, moet elke afzonderlijk worden verwijderd. Het verwijderen van een capture-listener heeft geen invloed op een niet-capture versie van dezelfde listener, en omgekeerd. |

### Zie ook

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
