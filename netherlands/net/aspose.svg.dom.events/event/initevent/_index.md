---
title: "Event.InitEvent"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Event InitEvent‑methode. De InitEvent‑methode wordt gebruikt om de waarde van een Event te initialiseren die via de IDocumentEvent‑interface is gemaakt."
type: docs
weight: 110
url: /nl/net/aspose.svg.dom.events/event/initevent/
---
## Event.InitEvent method

De `InitEvent`‑methode wordt gebruikt om de waarde van een [`Event`](../) te initialiseren die via de [`IDocumentEvent`](../../idocumentevent/)‑interface is gemaakt.

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Het gebeurtenistype. |
| bubbles | Boolean | indien ingesteld op `true` [bubbles]. |
| cancelable | Boolean | indien ingesteld op `true` [cancelable]. |

## Opmerkingen

Deze methode mag alleen worden aangeroepen voordat het Event is verzonden via de [`DispatchEvent`](../../ieventtarget/dispatchevent/) methode, hoewel hij indien nodig meerdere keren tijdens die fase kan worden aangeroepen. Als hij meerdere keren wordt aangeroepen, heeft de laatste aanroep voorrang. Als hij wordt aangeroepen vanuit een subklasse van de Event-interface, worden alleen de waarden die in de initEvent-methode zijn gespecificeerd aangepast; alle andere attributen blijven ongewijzigd.

### Zie ook

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
