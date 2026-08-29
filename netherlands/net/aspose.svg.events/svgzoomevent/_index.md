---
title: "SVGZoomEvent Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Events.SVGZoomEvent class. Het zoom‑event treedt op wanneer de gebruiker een actie start die ervoor zorgt dat de huidige weergave van het SVG‑documentfragment wordt herschaald. Event‑handlers worden alleen herkend op svg‑elementen."
type: docs
weight: 3710
url: /nl/net/aspose.svg.events/svgzoomevent/
---
## SVGZoomEvent class

De zoomevenement treedt op wanneer de gebruiker een actie start die ervoor zorgt dat de huidige weergave van het SVG‑documentfragment wordt geschaald. Event‑handlers worden alleen herkend op ‘svg’-elementen.

```csharp
public class SVGZoomEvent : Event
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Wordt gebruikt om aan te geven of een gebeurtenis een bubbling‑gebeurtenis is of niet. Als de gebeurtenis kan bubbelen, is de waarde true, anders is de waarde false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Wordt gebruikt om aan te geven of de standaardactie van een gebeurtenis kan worden voorkomen. Als de standaardactie kan worden voorkomen, is de waarde true, anders is de waarde false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Wordt gebruikt om het [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) aan te geven waarvan de [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)s momenteel worden verwerkt. Dit is bijzonder nuttig tijdens het vastleggen en bubbelen. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Retourneert true als preventDefault() werd aangeroepen terwijl de waarde van het attribuut cancelable true is, en anders false. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Het attribuut isTrusted moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer een gebeurtenis wordt aangemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [NewScale](../../aspose.svg.events/svgzoomevent/newscale/) { get; } | De schaalfactor die van kracht zal zijn nadat de zoombewerking is verwerkt. |
| [NewTranslate](../../aspose.svg.events/svgzoomevent/newtranslate/) { get; } | De translatie‑waarden die van kracht zullen zijn nadat de zoombewerking is verwerkt. Het SVGPoint‑object is alleen-lezen. |
| [PreviousScale](../../aspose.svg.events/svgzoomevent/previousscale/) { get; } | De schaalfactor van eerdere zoombewerkingen die van kracht was voordat de zoombewerking plaatsvond. |
| [PreviousTranslate](../../aspose.svg.events/svgzoomevent/previoustranslate/) { get; } | De translatie‑waarden van eerdere zoombewerkingen die van kracht waren voordat de zoombewerking plaatsvond. Het SVGPoint‑object is alleen-lezen. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Wordt gebruikt om het [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) aan te geven waarnaar het event oorspronkelijk is verzonden. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Wordt gebruikt om de tijd (in milliseconden ten opzichte van het epoch) op te geven waarop de gebeurtenis werd aangemaakt. Omdat sommige systemen deze informatie mogelijk niet leveren, kan de waarde van timeStamp voor sommige gebeurtenissen ontbreken. Wanneer deze niet beschikbaar is, wordt een waarde van 0 geretourneerd. Voorbeelden van epoch‑tijd zijn de tijd van het systeemstart of 0:0:0 UTC 1 januari 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | De naam van de gebeurtenis (niet‑hoofdlettergevoelig). De naam moet een XML‑naam zijn. |
| [ZoomRectScreen](../../aspose.svg.events/svgzoomevent/zoomrectscreen/) { get; } | Het opgegeven zoom‑rechthoek in schermeenheden. Het SVGRect‑object is alleen-lezen. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | De [`InitEvent`](../../aspose.svg.dom.events/event/initevent/)‑methode wordt gebruikt om de waarde van een [`Event`](../../aspose.svg.dom.events/event/) te initialiseren die via de [`IDocumentEvent`](../../aspose.svg.dom.events/idocumentevent/)‑interface is gemaakt. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Als een event annuleerbaar is, wordt de [`PreventDefault`](../../aspose.svg.dom.events/event/preventdefault/)‑methode gebruikt om aan te geven dat het event moet worden geannuleerd, wat betekent dat elke standaardactie die normaal door de implementatie zou worden uitgevoerd als gevolg van het event niet zal plaatsvinden. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Het aanroepen van deze methode voorkomt dat de gebeurtenis eventuele event‑listeners bereikt die na de huidige zijn geregistreerd en, wanneer deze in een boom wordt verzonden, voorkomt het ook dat de gebeurtenis andere objecten bereikt. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | De [`StopPropagation`](../../aspose.svg.dom.events/event/stoppropagation/)‑methode wordt gebruikt om verdere propagatie van een event tijdens de event‑stroom te voorkomen. |

### Zie ook

* class [Event](../../aspose.svg.dom.events/event/)
* namespace [Aspose.Svg.Events](../../aspose.svg.events/)
* assembly [Aspose.SVG](../../)
