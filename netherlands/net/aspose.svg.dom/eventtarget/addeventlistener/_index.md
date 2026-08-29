---
title: "EventTarget.AddEventListener"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "EventTarget AddEventListener‑methode. Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven event aan het doel wordt geleverd"
type: docs
weight: 20
url: /nl/net/aspose.svg.dom/eventtarget/addeventlistener/
---
## AddEventListener(*string, [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/), bool*) {#addeventlistener}

Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd.

Het werkt door een functie toe te voegen, of een object dat [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) implementeert, aan de lijst van event listeners voor het opgegeven evenementtype op de [`EventTarget`](../) waarop het wordt aangeroepen. Als de functie of het object al in de lijst van event listeners voor dit doel staat, worden ze niet een tweede keer toegevoegd.

```csharp
public void AddEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Het gebeurtenistype waarvoor de gebruiker registreert |
| handler | DOMEventHandler | Neemt een [`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/) dat wordt aangeroepen wanneer het evenement plaatsvindt. |
| useCapture | Boolean | Als true, geeft useCapture aan dat de gebruiker capture wil starten. Na het starten van capture worden alle events van het opgegeven type naar de geregistreerde [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) verzonden voordat ze naar enige Event Targets onder hen in de boom worden verzonden. Events die omhoog door de boom bubbelen zullen geen [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) activeren dat is aangewezen om capture te gebruiken. |

## Opmerkingen

Als een [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) wordt toegevoegd aan een [`EventTarget`](../) terwijl deze een event verwerkt, wordt hij niet geactiveerd door de huidige acties maar kan hij wel geactiveerd worden tijdens een later stadium van de eventstroom, zoals de bubbling-fase.

Als meerdere identieke Event Listeners zijn geregistreerd op dezelfde [`EventTarget`](../) met dezelfde parameters, worden de dubbele exemplaren verwijderd. Ze zorgen er niet voor dat de [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) twee keer wordt aangeroepen en aangezien ze worden verwijderd, hoeven ze niet te worden verwijderd met de [`RemoveEventListener`](../removeeventlistener/) methode.

### Zie ook

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)*) {#addeventlistener_1}

Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd.

Het werkt door een functie toe te voegen, of een object dat [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) implementeert, aan de lijst van event listeners voor het opgegeven evenementtype op de [`EventTarget`](../) waarop het wordt aangeroepen. Als de functie of het object al in de lijst van event listeners voor dit doel staat, worden ze niet een tweede keer toegevoegd.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Het gebeurtenistype waarvoor de gebruiker registreert |
| listener | IEventListener | Neemt een door de gebruiker geïmplementeerde interface die de methoden bevat die moeten worden aangeroepen wanneer het event plaatsvindt. |

## Opmerkingen

Als een [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) wordt toegevoegd aan een [`EventTarget`](../) terwijl deze een event verwerkt, wordt hij niet geactiveerd door de huidige acties maar kan hij wel geactiveerd worden tijdens een later stadium van de eventstroom, zoals de bubbling-fase.

Als meerdere identieke Event Listeners zijn geregistreerd op dezelfde [`EventTarget`](../) met dezelfde parameters, worden de dubbele exemplaren verwijderd. Ze zorgen er niet voor dat de [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) twee keer wordt aangeroepen en aangezien ze worden verwijderd, hoeven ze niet te worden verwijderd met de [`RemoveEventListener`](../removeeventlistener/) methode.

### Zie ook

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/), bool*) {#addeventlistener_2}

Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd.

Het werkt door een functie toe te voegen, of een object dat [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) implementeert, aan de lijst van event listeners voor het opgegeven evenementtype op de [`EventTarget`](../) waarop het wordt aangeroepen. Als de functie of het object al in de lijst van event listeners voor dit doel staat, worden ze niet een tweede keer toegevoegd.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Het gebeurtenistype waarvoor de gebruiker registreert |
| listener | IEventListener | Neemt een door de gebruiker geïmplementeerde interface die de methoden bevat die moeten worden aangeroepen wanneer het event plaatsvindt. |
| useCapture | Boolean | Als true, geeft useCapture aan dat de gebruiker capture wil starten. Na het starten van capture worden alle events van het opgegeven type naar de geregistreerde [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) verzonden voordat ze naar enige Event Targets onder hen in de boom worden verzonden. Events die omhoog door de boom bubbelen zullen geen [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) activeren dat is aangewezen om capture te gebruiken. |

## Opmerkingen

Als een [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) wordt toegevoegd aan een [`EventTarget`](../) terwijl deze een event verwerkt, wordt hij niet geactiveerd door de huidige acties maar kan hij wel geactiveerd worden tijdens een later stadium van de eventstroom, zoals de bubbling-fase.

Als meerdere identieke Event Listeners zijn geregistreerd op dezelfde [`EventTarget`](../) met dezelfde parameters, worden de dubbele exemplaren verwijderd. Ze zorgen er niet voor dat de [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) twee keer wordt aangeroepen en aangezien ze worden verwijderd, hoeven ze niet te worden verwijderd met de [`RemoveEventListener`](../removeeventlistener/) methode.

### Zie ook

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
