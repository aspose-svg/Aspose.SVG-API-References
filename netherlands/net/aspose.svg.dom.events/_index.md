---
title: "Aspose.Svg.Dom.Events"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "De Aspose.Svg.Dom.Events‑namespace biedt objecten voor alle gebeurtenissen die verband houden met DOM‑updates. Het omvat abonnement op specifieke contextuele informatie‑observatie die aan een gebeurtenis is gekoppeld, evenals de constructie van aangepaste gebeurtenissen."
type: docs
weight: 100
url: /nl/net/aspose.svg.dom.events/
---
De **Aspose.Svg.Dom.Events** naamruimte biedt objecten voor alle gebeurtenissen die verband houden met DOM‑updates. Ze omvat een abonnement op specifieke contextuele informatieobservatie die aan een gebeurtenis is gekoppeld, evenals de constructie van aangepaste gebeurtenissen.

## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [CustomEvent](./customevent/) | Gebeurtenissen die de CustomEvent‑interface gebruiken, kunnen worden gebruikt om aangepaste gegevens te dragen. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | De [`DocumentLoadErrorEvent`](../aspose.svg.dom.events/documentloaderrorevent/) treedt op wanneer de aangevraagde bron niet beschikbaar is. |
| [DOMEventHandler](./domeventhandler/) | Stelt de callback voor gebeurtenisafhandeling voor. |
| [ErrorEvent](./errorevent/) | De [`ErrorEvent`](../aspose.svg.dom.events/errorevent/) biedt contextuele informatie over fouten die zich tijdens runtime hebben voorgedaan. |
| [Event](./event/) | De [`Event`](../aspose.svg.dom.events/event/) wordt gebruikt om contextuele informatie over een gebeurtenis aan de handler die de gebeurtenis verwerkt te verstrekken. |
| [FocusEvent](./focusevent/) | De FocusEvent‑interface biedt specifieke contextuele informatie die verband houdt met focus‑gebeurtenissen. |
| [InputEvent](./inputevent/) | Invoergebeurtenissen worden verzonden als meldingen telkens wanneer de DOM wordt bijgewerkt. |
| [KeyboardEvent](./keyboardevent/) | De KeyboardEvent‑interface biedt specifieke contextuele informatie die verband houdt met toetsenbordapparaten. Elke toetsenbordgebeurtenis verwijst naar een toets via een waarde. Toetsenbordgebeurtenissen worden doorgaans gericht op het element dat de focus heeft. |
| [MouseEvent](./mouseevent/) | De MouseEvent‑interface biedt specifieke contextuele informatie die verband houdt met muisgebeurtenissen. |
| [UIEvent](./uievent/) | De UIEvent‑interface biedt specifieke contextuele informatie die verband houdt met gebruikersinterface‑gebeurtenissen. |
| [WheelEvent](./wheelevent/) | De WheelEvent‑interface biedt specifieke contextuele informatie die verband houdt met wiel‑gebeurtenissen. Om een instantie van de WheelEvent‑interface te maken, gebruik je de WheelEvent‑constructor en geef je een optionele WheelEventInit‑dictionary door. |
## Interfaces

| Interface | Beschrijving |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | De [`IDocumentEvent`](../aspose.svg.dom.events/idocumentevent/)‑interface biedt een mechanisme waarmee de gebruiker een [`Event`](../aspose.svg.dom.events/event/) van een type kan creëren dat door de implementatie wordt ondersteund. |
| [IEventListener](./ieventlistener/) | De [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) interface is de primaire methode voor het afhandelen van gebeurtenissen. Gebruikers implementeren de [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) interface en registreren hun listener op een [`EventTarget`](../aspose.svg.dom/eventtarget/) met behulp van de [`AddEventListener`](../aspose.svg.dom/eventtarget/addeventlistener/) methode. Gebruikers moeten ook hun [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) van het bijbehorende [`EventTarget`](../aspose.svg.dom/eventtarget/) verwijderen nadat ze klaar zijn met het gebruik van de listener. |
| [IEventTarget](./ieventtarget/) | De [`EventTarget`](../aspose.svg.dom/eventtarget/) interface wordt geïmplementeerd door alle Nodes in een implementatie die het DOM Event Model ondersteunt. Daarom kan deze interface verkregen worden door bindingspecifieke castmethoden te gebruiken op een instantie van de Node interface. De interface staat registratie en verwijdering van Event Listeners op een [`EventTarget`](../aspose.svg.dom/eventtarget/) toe en het verzenden van gebeurtenissen naar die [`IEventTarget`](../aspose.svg.dom.events/ieventtarget/). |
