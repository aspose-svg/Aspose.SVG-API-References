---
title: "DocumentLoadErrorEvent Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Events.DocumentLoadErrorEvent klasse. De DocumentLoadErrorEvent treedt op wanneer de aangevraagde bron niet beschikbaar is"
type: docs
weight: 2900
url: /nl/net/aspose.svg.dom.events/documentloaderrorevent/
---
## DocumentLoadErrorEvent class

De `DocumentLoadErrorEvent` treedt op wanneer de aangevraagde bron niet beschikbaar is.

```csharp
public class DocumentLoadErrorEvent : ErrorEvent
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | Wordt gebruikt om aan te geven of een gebeurtenis een bubbling‑gebeurtenis is of niet. Als de gebeurtenis kan bubbelen, is de waarde true, anders is de waarde false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | Wordt gebruikt om aan te geven of de standaardactie van een gebeurtenis kan worden voorkomen. Als de standaardactie kan worden voorkomen, is de waarde true, anders is de waarde false. |
| [ColNo](../../aspose.svg.dom.events/errorevent/colno/) { get; } | Het colno‑attribuut moet de waarde teruggeven waarmee het is geïnitialiseerd. Wanneer het object wordt aangemaakt, moet dit attribuut op nul worden geïnitialiseerd. Het vertegenwoordigt het kolomnummer waar de fout in het script optrad. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | Wordt gebruikt om het [`IEventTarget`](../ieventtarget/) aan te geven waarvan de [`IEventListener`](../ieventlistener/)s momenteel worden verwerkt. Dit is vooral nuttig tijdens capturing en bubbling. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | Retourneert true als preventDefault() werd aangeroepen terwijl de waarde van het attribuut cancelable true is, en anders false. |
| [Error](../../aspose.svg.dom.events/errorevent/error/) { get; } | Het attribuut error moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer het object wordt aangemaakt, moet dit attribuut worden geïnitialiseerd op null. Waar passend wordt het ingesteld op het object dat de fout vertegenwoordigt (bijv. het exceptie‑object in het geval van een niet‑afgevangen DOM‑exceptie). |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [FileName](../../aspose.svg.dom.events/errorevent/filename/) { get; } | Het attribuut filename moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer het object wordt aangemaakt, moet dit attribuut worden geïnitialiseerd op een lege tekenreeks. Het vertegenwoordigt de absolute URL van het script waarin de fout oorspronkelijk optrad. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | Het attribuut isTrusted moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer een gebeurtenis wordt aangemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [LineNo](../../aspose.svg.dom.events/errorevent/lineno/) { get; } | Het attribuut lineno moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer het object wordt aangemaakt, moet dit attribuut worden geïnitialiseerd op nul. Het vertegenwoordigt het regelnummer waarop de fout in het script optrad. |
| [Message](../../aspose.svg.dom.events/errorevent/message/) { get; } | Het attribuut message moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer het object wordt aangemaakt, moet dit attribuut worden geïnitialiseerd op een lege tekenreeks. Het vertegenwoordigt het foutbericht. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | Wordt gebruikt om de [`IEventTarget`](../ieventtarget/) aan te geven waarnaar de gebeurtenis oorspronkelijk werd verzonden. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | Wordt gebruikt om de tijd (in milliseconden ten opzichte van het epoch) op te geven waarop de gebeurtenis werd aangemaakt. Omdat sommige systemen deze informatie mogelijk niet leveren, kan de waarde van timeStamp voor sommige gebeurtenissen ontbreken. Wanneer deze niet beschikbaar is, wordt een waarde van 0 geretourneerd. Voorbeelden van epoch‑tijd zijn de tijd van het systeemstart of 0:0:0 UTC 1 januari 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | De naam van de gebeurtenis (niet‑hoofdlettergevoelig). De naam moet een XML‑naam zijn. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | De [`InitEvent`](../event/initevent/)‑methode wordt gebruikt om de waarde van een [`Event`](../event/) te initialiseren die via de [`IDocumentEvent`](../idocumentevent/)‑interface is aangemaakt. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | Als een gebeurtenis annuleerbaar is, wordt de [`PreventDefault`](../event/preventdefault/)‑methode gebruikt om aan te geven dat de gebeurtenis moet worden geannuleerd, wat betekent dat elke standaardactie die normaal door de implementatie zou worden uitgevoerd als gevolg van de gebeurtenis niet zal plaatsvinden. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | Het aanroepen van deze methode voorkomt dat de gebeurtenis eventuele event‑listeners bereikt die na de huidige zijn geregistreerd en, wanneer deze in een boom wordt verzonden, voorkomt het ook dat de gebeurtenis andere objecten bereikt. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | De [`StopPropagation`](../event/stoppropagation/)‑methode wordt gebruikt om verdere verspreiding van een gebeurtenis tijdens de gebeurtenisstroom te voorkomen. |

### Zie ook

* class [ErrorEvent](../errorevent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
