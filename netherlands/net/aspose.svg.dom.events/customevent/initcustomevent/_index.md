---
title: "CustomEvent.InitCustomEvent"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "CustomEvent InitCustomEvent methode. /// De InitEvent-methode wordt gebruikt om de waarde van een Event te initialiseren die via de IDocumentEvent-interface is gemaakt"
type: docs
weight: 30
url: /nl/net/aspose.svg.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// De [`InitEvent`](../../event/initevent/) methode wordt gebruikt om de waarde van een [`Event`](../../event/) te initialiseren die via de [`IDocumentEvent`](../../idocumentevent/) interface is gemaakt.

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Het gebeurtenistype. |
| bubbles | Boolean | indien ingesteld op `true` [bubbles]. |
| cancelable | Boolean | indien ingesteld op `true` [cancelable]. |
| detail | Object | De aangepaste gegevens. |

## Opmerkingen

Deze methode mag alleen worden aangeroepen voordat het Event is verzonden via de [`DispatchEvent`](../../ieventtarget/dispatchevent/) methode, hoewel hij indien nodig meerdere keren tijdens die fase kan worden aangeroepen. Als hij meerdere keren wordt aangeroepen, heeft de laatste aanroep voorrang. Als hij wordt aangeroepen vanuit een subklasse van de Event-interface, worden alleen de waarden die in de initEvent-methode zijn gespecificeerd aangepast; alle andere attributen blijven ongewijzigd.

### Zie ook

* class [CustomEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
