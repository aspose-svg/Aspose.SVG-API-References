---
title: "KeyboardEvent‑klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Events.KeyboardEvent‑klasse. De KeyboardEvent‑interface biedt specifieke contextuele informatie die verband houdt met toetsenbordapparaten. Elke toetsenbordgebeurtenis verwijst naar een toets via een waarde. Toetsenbordgebeurtenissen worden meestal gericht op het element dat de focus heeft."
type: docs
weight: 2980
url: /nl/net/aspose.svg.dom.events/keyboardevent/
---
## KeyboardEvent class

De KeyboardEvent‑interface biedt specifieke contextuele informatie die verband houdt met toetsenbordapparaten. Elke toetsenbordgebeurtenis verwijst naar een toets via een waarde. Toetsenbordgebeurtenissen worden doorgaans gericht op het element dat de focus heeft.

```csharp
public class KeyboardEvent : UIEvent
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(*string*) | Initialiseert een nieuw exemplaar van de `KeyboardEvent`‑klasse. |
| [KeyboardEvent](keyboardevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | Initialiseert een nieuw exemplaar van de `KeyboardEvent`‑klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AltKey](../../aspose.svg.dom.events/keyboardevent/altkey/) { get; } | true als de Alt‑ (alternatieve) (of "Option")‑toetsmodifier actief was. De niet‑geïnitialiseerde waarde van dit attribuut MOET false zijn. |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Wordt gebruikt om aan te geven of een gebeurtenis een bubbling‑gebeurtenis is of niet. Als de gebeurtenis kan bubbelen, is de waarde true, anders is de waarde false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Wordt gebruikt om aan te geven of de standaardactie van een gebeurtenis kan worden voorkomen. Als de standaardactie kan worden voorkomen, is de waarde true, anders is de waarde false. |
| [Code](../../aspose.svg.dom.events/keyboardevent/code/) { get; } | De code bevat een tekenreeks die de fysieke toets identificeert die wordt ingedrukt. De waarde wordt niet beïnvloed door de huidige toetsenbordindeling of modifier‑status, zodat een bepaalde toets altijd dezelfde waarde retourneert. |
| [CtrlKey](../../aspose.svg.dom.events/keyboardevent/ctrlkey/) { get; } | true als de Control‑ (control)‑toetsmodifier actief was. De niet‑geïnitialiseerde waarde van dit attribuut MOET false zijn. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Wordt gebruikt om het [`IEventTarget`](../ieventtarget/) aan te geven waarvan de [`IEventListener`](../ieventlistener/)s momenteel worden verwerkt. Dit is vooral nuttig tijdens capturing en bubbling. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Retourneert true als preventDefault() werd aangeroepen terwijl de waarde van het attribuut cancelable true is, en anders false. |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | Specificeert enige detailinformatie over de gebeurtenis, afhankelijk van het type gebeurtenis. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [IsComposing](../../aspose.svg.dom.events/keyboardevent/iscomposing/) { get; } | true als de toetsenbordgebeurtenis plaatsvindt als onderdeel van een compositiesessie, d.w.z. na een compositionstart‑gebeurtenis en vóór de bijbehorende compositionend‑gebeurtenis. De niet‑geïnitialiseerde waarde van dit attribuut MOET false zijn. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Het attribuut isTrusted moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer een gebeurtenis wordt aangemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [Key](../../aspose.svg.dom.events/keyboardevent/key/) { get; } | De toets bevat de toetswaarde van de ingedrukte toets. Als de waarde een afgedrukte weergave heeft, MOET het een niet-lege Unicode‑tekenreeks zijn, die voldoet aan het algoritme voor het bepalen van de toetswaarde zoals gedefinieerd in deze specificatie. Als de waarde een controle‑toets is die geen afgedrukte weergave heeft, MOET het een van de in de set toetswaarden gedefinieerde toetswaarden zijn, zoals bepaald door het algoritme voor het bepalen van de toetswaarde. Implementaties die niet in staat zijn een toets te identificeren MOETEN de toetswaarde Unidentified gebruiken. |
| [Location](../../aspose.svg.dom.events/keyboardevent/location/) { get; } | Het attribuut location bevat een indicatie van de logische locatie van de toets op het apparaat. |
| [MetaKey](../../aspose.svg.dom.events/keyboardevent/metakey/) { get; } | true als de meta (Meta) toetsmodifier actief was. |
| [Repeat](../../aspose.svg.dom.events/keyboardevent/repeat/) { get; } | true als de toets gedurende een langere tijd is ingedrukt. Het ingedrukt houden van een toets MOET resulteren in het herhalen van de gebeurtenissen keydown, beforeinput, input in deze volgorde, met een snelheid bepaald door de systeemconfiguratie. Voor mobiele apparaten die een lang‑toets‑indruk gedrag hebben, moet het eerste toetsevent met een repeat‑attribuutwaarde van true dienen als een indicatie van een lang‑toets‑indruk. De tijdsduur dat de toets MOET worden ingedrukt om te beginnen met herhalen is afhankelijk van de configuratie. |
| [ShiftKey](../../aspose.svg.dom.events/keyboardevent/shiftkey/) { get; } | true als de shift (Shift) toetsmodifier actief was. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Wordt gebruikt om de [`IEventTarget`](../ieventtarget/) aan te geven waarnaar de gebeurtenis oorspronkelijk werd verzonden. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Wordt gebruikt om de tijd (in milliseconden ten opzichte van het epoch) op te geven waarop de gebeurtenis werd aangemaakt. Omdat sommige systemen deze informatie mogelijk niet leveren, kan de waarde van timeStamp voor sommige gebeurtenissen ontbreken. Wanneer deze niet beschikbaar is, wordt een waarde van 0 geretourneerd. Voorbeelden van epoch‑tijd zijn de tijd van het systeemstart of 0:0:0 UTC 1 januari 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | De naam van de gebeurtenis (niet‑hoofdlettergevoelig). De naam moet een XML‑naam zijn. |
| [View](../../aspose.svg.dom.events/uievent/view/) { get; } | Het attribuut view identificeert het Window waaruit het event is gegenereerd. De niet‑geïnitiseerde waarde van dit attribuut MOET null zijn. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | De [`InitEvent`](../event/initevent/)‑methode wordt gebruikt om de waarde van een [`Event`](../event/) te initialiseren die via de [`IDocumentEvent`](../idocumentevent/)‑interface is aangemaakt. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Als een gebeurtenis annuleerbaar is, wordt de [`PreventDefault`](../event/preventdefault/)‑methode gebruikt om aan te geven dat de gebeurtenis moet worden geannuleerd, wat betekent dat elke standaardactie die normaal door de implementatie zou worden uitgevoerd als gevolg van de gebeurtenis niet zal plaatsvinden. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Het aanroepen van deze methode voorkomt dat de gebeurtenis eventuele event‑listeners bereikt die na de huidige zijn geregistreerd en, wanneer deze in een boom wordt verzonden, voorkomt het ook dat de gebeurtenis andere objecten bereikt. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | De [`StopPropagation`](../event/stoppropagation/)‑methode wordt gebruikt om verdere verspreiding van een gebeurtenis tijdens de gebeurtenisstroom te voorkomen. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../aspose.svg.dom.events/keyboardevent/dom_key_location_left/) | De geactiveerde toets kwam voort uit de linker‑toetslocatie (wanneer er meer dan één mogelijke locatie voor deze toets is). |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.svg.dom.events/keyboardevent/dom_key_location_numpad/) | De toetsactivatie kwam voort uit het numerieke toetsenbord of met een virtuele toets die overeenkomt met het numerieke toetsenbord (wanneer er meer dan één mogelijke locatie voor deze toets is). Merk op dat de NumLock‑toets altijd moet worden gecodeerd met een locatie van DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.svg.dom.events/keyboardevent/dom_key_location_right/) | De toetsactivatie kwam voort uit de rechter‑toetslocatie (wanneer er meer dan één mogelijke locatie voor deze toets is). |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.svg.dom.events/keyboardevent/dom_key_location_standard/) | De toetsactivatie MAG NIET worden onderscheiden als de linker‑ of rechterversie van de toets, en (anders dan de NumLock‑toets) kwam niet voort uit het numerieke toetsenbord (of kwam niet voort uit een virtuele toets die overeenkomt met het numerieke toetsenbord). |

### Zie ook

* class [UIEvent](../uievent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
