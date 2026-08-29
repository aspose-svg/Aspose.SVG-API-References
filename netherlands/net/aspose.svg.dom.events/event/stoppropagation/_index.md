---
title: "Event.StopPropagation"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Event StopPropagation methode. De StopPropagation-methode wordt gebruikt om verdere verspreiding van een gebeurtenis tijdens de gebeurtenisstroom te voorkomen"
type: docs
weight: 140
url: /nl/net/aspose.svg.dom.events/event/stoppropagation/
---
## Event.StopPropagation method

De `StopPropagation`-methode wordt gebruikt om verdere verspreiding van een gebeurtenis tijdens de gebeurtenisstroom te voorkomen.

```csharp
public void StopPropagation()
```

## Opmerkingen

Als deze methode wordt aangeroepen door een [`IEventListener`](../../ieventlistener/) zal de gebeurtenis stoppen met zich voort te planten door de boom. De gebeurtenis zal de verzending naar alle luisteraars op de huidige [`IEventTarget`](../../ieventtarget/) voltooien voordat de gebeurtenisstroom stopt. Deze methode kan tijdens elke fase van de gebeurtenisstroom worden gebruikt.

### Zie ook

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
