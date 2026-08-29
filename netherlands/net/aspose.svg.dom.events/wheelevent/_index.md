---
title: "WheelEvent Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Events.WheelEvent klasse. De WheelEvent interface biedt specifieke contextuele informatie die verband houdt met wiel‑gebeurtenissen. Om een instantie van de WheelEvent interface te maken, gebruik de WheelEvent‑constructor met een optioneel WheelEventInit‑woordenboek"
type: docs
weight: 3010
url: /nl/net/aspose.svg.dom.events/wheelevent/
---
## WheelEvent class

De WheelEvent‑interface biedt specifieke contextuele informatie die verband houdt met wiel‑gebeurtenissen. Om een instantie van de WheelEvent‑interface te maken, gebruik je de WheelEvent‑constructor en geef je een optionele WheelEventInit‑dictionary door.

```csharp
public class WheelEvent : MouseEvent
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(*string*) | Initialiseert een nieuwe instantie van de `WheelEvent` klasse. |
| [WheelEvent](wheelevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | Initialiseert een nieuwe instantie van de `WheelEvent` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AltKey](../../aspose.svg.dom.events/mouseevent/altkey/) { get; } | Verwijs naar het altKey-attribuut. |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Wordt gebruikt om aan te geven of een gebeurtenis een bubbling‑gebeurtenis is of niet. Als de gebeurtenis kan bubbelen, is de waarde true, anders is de waarde false. |
| [Button](../../aspose.svg.dom.events/mouseevent/button/) { get; } | Tijdens muisgebeurtenissen veroorzaakt door het indrukken of loslaten van een muisknop, button MUST worden gebruikt om aan te geven welke aanwijzerapparaatknop van toestand is veranderd. |
| [Buttons](../../aspose.svg.dom.events/mouseevent/buttons/) { get; } | Tijdens alle muisgebeurtenissen, buttons MUST worden gebruikt om aan te geven welke combinatie van muisknoppen momenteel wordt ingedrukt, uitgedrukt als een bitmasker. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Wordt gebruikt om aan te geven of de standaardactie van een gebeurtenis kan worden voorkomen. Als de standaardactie kan worden voorkomen, is de waarde true, anders is de waarde false. |
| [ClientX](../../aspose.svg.dom.events/mouseevent/clientx/) { get; } | De horizontale coördinaat waarop het evenement plaatsvond ten opzichte van de viewport die aan het evenement is gekoppeld. |
| [ClientY](../../aspose.svg.dom.events/mouseevent/clienty/) { get; } | De verticale coördinaat waarop het evenement plaatsvond ten opzichte van de viewport die aan het evenement is gekoppeld. |
| [CtrlKey](../../aspose.svg.dom.events/mouseevent/ctrlkey/) { get; } | Verwijs naar het ctrlKey-attribuut. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Wordt gebruikt om het [`IEventTarget`](../ieventtarget/) aan te geven waarvan de [`IEventListener`](../ieventlistener/)s momenteel worden verwerkt. Dit is vooral nuttig tijdens capturing en bubbling. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Retourneert true als preventDefault() werd aangeroepen terwijl de waarde van het attribuut cancelable true is, en anders false. |
| [DeltaMode](../../aspose.svg.dom.events/wheelevent/deltamode/) { get; } | Het deltaMode‑attribuut bevat een indicatie van de meeteenheden voor de delta‑waarden. De standaardwaarde is DOM_DELTA_PIXEL (pixels). |
| [DeltaX](../../aspose.svg.dom.events/wheelevent/deltax/) { get; } | In user agents waar de standaardactie van de wheel‑event is om te scrollen, moet de waarde de meting langs de x-as (in pixels, regels of pagina's) zijn die moet worden gescrold in het geval dat de gebeurtenis niet wordt geannuleerd. Anders is dit een implementatie‑specifieke meting (in pixels, regels of pagina's) van de beweging van een wielapparaat rond de x-as. |
| [DeltaY](../../aspose.svg.dom.events/wheelevent/deltay/) { get; } | In user agents waar de standaardactie van de wheel‑event is om te scrollen, moet de waarde de meting langs de y-as (in pixels, regels of pagina's) zijn die moet worden gescrold in het geval dat de gebeurtenis niet wordt geannuleerd. Anders is dit een implementatie‑specifieke meting (in pixels, regels of pagina's) van de beweging van een wielapparaat rond de y-as. |
| [DeltaZ](../../aspose.svg.dom.events/wheelevent/deltaz/) { get; } | In user agents waar de standaardactie van de wheel‑event is om te scrollen, moet de waarde de meting langs de z-as (in pixels, regels of pagina's) zijn die moet worden gescrold in het geval dat de gebeurtenis niet wordt geannuleerd. Anders is dit een implementatie‑specifieke meting (in pixels, regels of pagina's) van de beweging van een wielapparaat rond de z-as. |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | Specificeert enige detailinformatie over de gebeurtenis, afhankelijk van het type gebeurtenis. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Het attribuut isTrusted moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer een gebeurtenis wordt aangemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [MetaKey](../../aspose.svg.dom.events/mouseevent/metakey/) { get; } | Verwijs naar het metaKey-attribuut. |
| [RelatedTarget](../../aspose.svg.dom.events/mouseevent/relatedtarget/) { get; } | Wordt gebruikt om een secundaire EventTarget te identificeren die gerelateerd is aan een UI-evenement, afhankelijk van het type evenement. |
| [ScreenX](../../aspose.svg.dom.events/mouseevent/screenx/) { get; } | De horizontale coördinaat waarop het evenement plaatsvond ten opzichte van de oorsprong van het schermcoördinatensysteem. |
| [ScreenY](../../aspose.svg.dom.events/mouseevent/screeny/) { get; } | De verticale coördinaat waarop het evenement plaatsvond ten opzichte van de oorsprong van het schermcoördinatensysteem. |
| [ShiftKey](../../aspose.svg.dom.events/mouseevent/shiftkey/) { get; } | Verwijs naar het shiftKey-attribuut. |
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
| const [DOM_DELTA_LINE](../../aspose.svg.dom.events/wheelevent/dom_delta_line/) | De meeteenheden voor de delta MOETEN individuele tekstregels zijn. Dit is het geval voor veel formulier‑besturingselementen. |
| const [DOM_DELTA_PAGE](../../aspose.svg.dom.events/wheelevent/dom_delta_page/) | De meeteenheden voor de delta MOETEN pagina's zijn, gedefinieerd als een enkel scherm of als een afgebakende pagina. |
| const [DOM_DELTA_PIXEL](../../aspose.svg.dom.events/wheelevent/dom_delta_pixel/) | De meeteenheden voor de delta MOETEN pixels zijn. Dit is het meest voorkomende geval in de meeste besturingssystemen en implementatie‑configuraties. |

### Zie ook

* class [MouseEvent](../mouseevent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
