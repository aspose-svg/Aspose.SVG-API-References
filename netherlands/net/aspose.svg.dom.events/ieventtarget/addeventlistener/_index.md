---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "IEventTarget AddEventListener-methode. Deze methode maakt de registratie van event listeners op het eventdoel mogelijk."
type: docs
weight: 10
url: /nl/net/aspose.svg.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(*string, [IEventListener](../../ieventlistener/)*) {#addeventlistener}

Deze methode maakt de registratie van event listeners op het event‑doel mogelijk.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Het gebeurtenistype waarvoor de gebruiker registreert |
| listener | IEventListener | Neemt een door de gebruiker geïmplementeerde interface die de methoden bevat die moeten worden aangeroepen wanneer het event plaatsvindt. |

## Opmerkingen

Als een [`IEventListener`](../../ieventlistener/) wordt toegevoegd aan een [`EventTarget`](../../../aspose.svg.dom/eventtarget/) terwijl deze een gebeurtenis verwerkt, wordt deze niet geactiveerd door de huidige acties, maar kan later in de gebeurtenisstroom, bijvoorbeeld tijdens de bubbling-fase, worden geactiveerd.

Als meerdere identieke Event Listeners op dezelfde [`EventTarget`](../../../aspose.svg.dom/eventtarget/) met dezelfde parameters worden geregistreerd, worden de dubbele exemplaren verwijderd. Ze zorgen er niet voor dat de [`IEventListener`](../../ieventlistener/) twee keer wordt aangeroepen en omdat ze worden verwijderd, hoeven ze niet te worden verwijderd met de [`RemoveEventListener`](../removeeventlistener/) methode.

### Zie ook

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../ieventlistener/), bool*) {#addeventlistener_1}

Deze methode maakt de registratie van event listeners op het event‑doel mogelijk.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Het gebeurtenistype waarvoor de gebruiker registreert |
| listener | IEventListener | Neemt een door de gebruiker geïmplementeerde interface die de methoden bevat die moeten worden aangeroepen wanneer het event plaatsvindt. |
| useCapture | Boolean | Als true, geeft useCapture aan dat de gebruiker capture wil starten. Na het starten van capture worden alle events van het opgegeven type eerst verzonden naar de geregistreerde [`IEventListener`](../../ieventlistener/) voordat ze worden verzonden naar eventuele Event Targets onder hen in de boom. Events die omhoog bubbelen door de boom zullen geen [`IEventListener`](../../ieventlistener/) activeren die is aangewezen om capture te gebruiken. |

## Opmerkingen

Als een [`IEventListener`](../../ieventlistener/) wordt toegevoegd aan een [`EventTarget`](../../../aspose.svg.dom/eventtarget/) terwijl deze een gebeurtenis verwerkt, wordt deze niet geactiveerd door de huidige acties, maar kan later in de gebeurtenisstroom, bijvoorbeeld tijdens de bubbling-fase, worden geactiveerd.

Als meerdere identieke Event Listeners op dezelfde [`EventTarget`](../../../aspose.svg.dom/eventtarget/) met dezelfde parameters worden geregistreerd, worden de dubbele exemplaren verwijderd. Ze zorgen er niet voor dat de [`IEventListener`](../../ieventlistener/) twee keer wordt aangeroepen en omdat ze worden verwijderd, hoeven ze niet te worden verwijderd met de [`RemoveEventListener`](../removeeventlistener/) methode.

### Zie ook

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
