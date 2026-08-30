---
title: "Aspose.Svg.Dom.Events"
second_title: "Aspose.SVG för .NET API-referens"
description: "Den Aspose.Svg.Dom.Events-namespace tillhandahåller objekt för alla händelser relaterade till DOM-uppdatering. Det inkluderar prenumeration på specifik kontextuell informationsobservation som är associerad med händelsen samt konstruktion av anpassade händelser."
type: docs
weight: 100
url: /sv/net/aspose.svg.dom.events/
---
Namnrummet **Aspose.Svg.Dom.Events** tillhandahåller objekt för alla händelser relaterade till DOM‑uppdateringar. Det inkluderar prenumeration på specifik kontextuell informationsobservation kopplad till händelsen samt konstruktion av anpassade händelser.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [CustomEvent](./customevent/) | Händelser som använder CustomEvent-gränssnittet kan användas för att bära anpassade data. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | Den [`DocumentLoadErrorEvent`](../aspose.svg.dom.events/documentloaderrorevent/) inträffar när den begärda resursen inte är tillgänglig. |
| [DOMEventHandler](./domeventhandler/) | Representerar återanropet för händelsehantering. |
| [ErrorEvent](./errorevent/) | Den [`ErrorEvent`](../aspose.svg.dom.events/errorevent/) tillhandahåller kontextuell information om ett fel som inträffade under körning. |
| [Event](./event/) | Den [`Event`](../aspose.svg.dom.events/event/) används för att tillhandahålla kontextuell information om en händelse till hanteraren som bearbetar händelsen. |
| [FocusEvent](./focusevent/) | FocusEvent-gränssnittet tillhandahåller specifik kontextuell information som är associerad med fokus‑händelser. |
| [InputEvent](./inputevent/) | Inmatningshändelser skickas som aviseringar närhelst DOM uppdateras. |
| [KeyboardEvent](./keyboardevent/) | KeyboardEvent-gränssnittet tillhandahåller specifik kontextuell information som är associerad med tangentbordsenheter. Varje tangentbordshändelse refererar till en tangent med ett värde. Tangentbordshändelser riktas vanligtvis mot det element som har fokus. |
| [MouseEvent](./mouseevent/) | MouseEvent-gränssnittet tillhandahåller specifik kontextuell information som är associerad med mus‑händelser. |
| [UIEvent](./uievent/) | UIEvent-gränssnittet tillhandahåller specifik kontextuell information som är associerad med användargränssnittshändelser. |
| [WheelEvent](./wheelevent/) | WheelEvent-gränssnittet tillhandahåller specifik kontextuell information som är associerad med hjulhändelser. För att skapa en instans av WheelEvent‑gränssnittet, använd WheelEvent‑konstruktorn och skicka ett valfritt WheelEventInit‑lexikon. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | Den [`IDocumentEvent`](../aspose.svg.dom.events/idocumentevent/) gränssnittet tillhandahåller en mekanism så att användaren kan skapa ett [`Event`](../aspose.svg.dom.events/event/) av en typ som stöds av implementationen. |
| [IEventListener](./ieventlistener/) | Den [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) gränssnittet är den primära metoden för att hantera händelser. Användare implementerar [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) gränssnittet och registrerar sin lyssnare på ett [`EventTarget`](../aspose.svg.dom/eventtarget/) med hjälp av [`AddEventListener`](../aspose.svg.dom/eventtarget/addeventlistener/) metoden. Användarna bör också ta bort sin [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) från dess [`EventTarget`](../aspose.svg.dom/eventtarget/) efter att de har avslutat användningen av lyssnaren. |
| [IEventTarget](./ieventtarget/) | Den [`EventTarget`](../aspose.svg.dom/eventtarget/) gränssnittet implementeras av alla noder i en implementation som stöder DOM‑händelsemodellen. Därför kan detta gränssnitt erhållas genom att använda bindningsspecifika kastmetoder på en instans av Node‑gränssnittet. Gränssnittet möjliggör registrering och borttagning av händelselyssnare på ett [`EventTarget`](../aspose.svg.dom/eventtarget/) samt sändning av händelser till det [`IEventTarget`](../aspose.svg.dom.events/ieventtarget/). |
