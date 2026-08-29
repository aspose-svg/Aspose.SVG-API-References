---
title: "TimeEvent Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Events.TimeEvent class. De TimeEvent‑interface biedt specifieke contextuele informatie die verband houdt met Time‑events. De verschillende soorten events die kunnen optreden zijn beginEvent, endEvent en repeatEvent."
type: docs
weight: 3720
url: /nl/net/aspose.svg.events/timeevent/
---
## TimeEvent class

De TimeEvent‑interface biedt specifieke contextuele informatie die verband houdt met tijdgebeurtenissen. De verschillende typen gebeurtenissen die kunnen optreden zijn: beginEvent, endEvent en repeatEvent.

```csharp
public class TimeEvent : Event
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Wordt gebruikt om aan te geven of een gebeurtenis een bubbling‑gebeurtenis is of niet. Als de gebeurtenis kan bubbelen, is de waarde true, anders is de waarde false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Wordt gebruikt om aan te geven of de standaardactie van een gebeurtenis kan worden voorkomen. Als de standaardactie kan worden voorkomen, is de waarde true, anders is de waarde false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Wordt gebruikt om het [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) aan te geven waarvan de [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)s momenteel worden verwerkt. Dit is bijzonder nuttig tijdens het vastleggen en bubbelen. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Retourneert true als preventDefault() werd aangeroepen terwijl de waarde van het attribuut cancelable true is, en anders false. |
| [Detail](../../aspose.svg.events/timeevent/detail/) { get; } | Specificeert enkele detailinformatie over het Event, afhankelijk van het type van het event. Voor dit eventtype geeft het het herhalingsnummer voor de animatie aan. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Het attribuut isTrusted moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer een gebeurtenis wordt aangemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Wordt gebruikt om het [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) aan te geven waarnaar het event oorspronkelijk is verzonden. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Wordt gebruikt om de tijd (in milliseconden ten opzichte van het epoch) op te geven waarop de gebeurtenis werd aangemaakt. Omdat sommige systemen deze informatie mogelijk niet leveren, kan de waarde van timeStamp voor sommige gebeurtenissen ontbreken. Wanneer deze niet beschikbaar is, wordt een waarde van 0 geretourneerd. Voorbeelden van epoch‑tijd zijn de tijd van het systeemstart of 0:0:0 UTC 1 januari 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | De naam van de gebeurtenis (niet‑hoofdlettergevoelig). De naam moet een XML‑naam zijn. |
| [View](../../aspose.svg.events/timeevent/view/) { get; } | Het view‑attribuut identificeert de AbstractView [DOM2VIEWS] waaruit het event is gegenereerd. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | De [`InitEvent`](../../aspose.svg.dom.events/event/initevent/)‑methode wordt gebruikt om de waarde van een [`Event`](../../aspose.svg.dom.events/event/) te initialiseren die via de [`IDocumentEvent`](../../aspose.svg.dom.events/idocumentevent/)‑interface is gemaakt. |
| [InitTimeEvent](../../aspose.svg.events/timeevent/inittimeevent/)(*string, [IAbstractView](../../aspose.svg.dom.views/iabstractview/), long*) | De initTimeEvent‑methode wordt gebruikt om de waarde van een TimeEvent te initialiseren die via de DocumentEvent‑interface is gemaakt. Deze methode mag alleen worden aangeroepen voordat de TimeEvent is verzonden via de dispatchEvent‑methode, hoewel hij indien nodig meerdere keren tijdens die fase kan worden aangeroepen. Als hij meerdere keren wordt aangeroepen, heeft de laatste aanroep voorrang. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Als een event annuleerbaar is, wordt de [`PreventDefault`](../../aspose.svg.dom.events/event/preventdefault/)‑methode gebruikt om aan te geven dat het event moet worden geannuleerd, wat betekent dat elke standaardactie die normaal door de implementatie zou worden uitgevoerd als gevolg van het event niet zal plaatsvinden. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Het aanroepen van deze methode voorkomt dat de gebeurtenis eventuele event‑listeners bereikt die na de huidige zijn geregistreerd en, wanneer deze in een boom wordt verzonden, voorkomt het ook dat de gebeurtenis andere objecten bereikt. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | De [`StopPropagation`](../../aspose.svg.dom.events/event/stoppropagation/)‑methode wordt gebruikt om verdere propagatie van een event tijdens de event‑stroom te voorkomen. |

### Zie ook

* class [Event](../../aspose.svg.dom.events/event/)
* namespace [Aspose.Svg.Events](../../aspose.svg.events/)
* assembly [Aspose.SVG](../../)
