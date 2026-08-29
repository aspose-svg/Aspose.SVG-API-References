---
title: "MediaQueryList Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Window.MediaQueryList klasse. Een MediaQueryList‑object slaat informatie op over een mediavraag die op een document wordt toegepast, met ondersteuning voor zowel directe als gebeurtenisgestuurde overeenstemming met de status van het document. Zie de CSSOM View Module-specificatie https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs
weight: 5960
url: /nl/net/aspose.svg.window/mediaquerylist/
---
## MediaQueryList class

Een MediaQueryList-object slaat informatie op over een mediavraag die op een document wordt toegepast, met ondersteuning voor zowel onmiddellijke als gebeurtenisgestuurde overeenstemming met de staat van het document. Zie de CSSOM View Module-specificatie: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```csharp
public class MediaQueryList : EventTarget
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Document](../../aspose.svg.window/mediaquerylist/document/) { get; } | Document dat aan het contextobject is gekoppeld. |
| [Matches](../../aspose.svg.window/mediaquerylist/matches/) { get; } | Een booleaanse waarde die true retourneert als het document momenteel overeenkomt met de mediavraaglijst, of false als dat niet het geval is. |
| [Media](../../aspose.svg.window/mediaquerylist/media/) { get; } | Een string die een geserialiseerde mediavraag vertegenwoordigt. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [AddListener](../../aspose.svg.window/mediaquerylist/addlistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Voeg MediaQueryList‑overeenstemmingsstatus‑wijzigings‑eventlistener toe. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Verzendt een Event naar het opgegeven [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/), (synchroon) en roept de betrokken EventListeners in de juiste volgorde aan. De normale regels voor eventverwerking (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op handmatig verzonden events met [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Voert door de applicatie gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Deze methode maakt het verwijderen van event listeners van het event‑target mogelijk. Als een [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een [`EventTarget`](../../aspose.svg.dom/eventtarget/) terwijl deze een event verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Deze methode maakt het verwijderen van event listeners van het event‑target mogelijk. Als een [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een [`EventTarget`](../../aspose.svg.dom/eventtarget/) terwijl deze een event verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Deze methode maakt het verwijderen van event listeners van het event‑target mogelijk. Als een [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) wordt verwijderd van een [`EventTarget`](../../aspose.svg.dom/eventtarget/) terwijl deze een event verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveListener](../../aspose.svg.window/mediaquerylist/removelistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Verwijder MediaQueryList‑overeenstemmingsstatus‑wijzigings‑eventlistener. |

## Evenementen

| Naam | Beschrijving |
| --- | --- |
| event [OnChange](../../aspose.svg.window/mediaquerylist/onchange/) | Event dat wordt afgevuurd op de MediaQueryList wanneer de overeenstemmingsstatus verandert. |

### Zie ook

* class [EventTarget](../../aspose.svg.dom/eventtarget/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
