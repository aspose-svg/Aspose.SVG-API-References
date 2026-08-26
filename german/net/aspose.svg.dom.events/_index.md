---
title: "Aspose.Svg.Dom.Events"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Der Aspose.Svg.Dom.Events-Namespace stellt Objekte für alle DOM-Aktualisierungsereignisse bereit. Er beinhaltet die Abonnierung spezifischer kontextbezogener Informationsbeobachtungen, die mit einem Ereignis verknüpft sind, sowie die Konstruktion benutzerdefinierter Ereignisse."
type: docs
weight: 100
url: /de/net/aspose.svg.dom.events/
---
Der **Aspose.Svg.Dom.Events** Namensraum stellt Objekte für alle Ereignisse im Zusammenhang mit DOM‑Aktualisierungen bereit. Er umfasst die Abonnierung spezifischer kontextbezogener Informationsbeobachtungen, die mit einem Ereignis verknüpft sind, sowie die Erstellung benutzerdefinierter Ereignisse.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [CustomEvent](./customevent/) | Ereignisse, die das CustomEvent-Interface verwenden, können zum Übertragen benutzerdefinierter Daten verwendet werden. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | Das [`DocumentLoadErrorEvent`](../aspose.svg.dom.events/documentloaderrorevent/) tritt auf, wenn die angeforderte Ressource nicht verfügbar ist. |
| [DOMEventHandler](./domeventhandler/) | Stellt den Rückruf für die Ereignisbehandlung dar. |
| [ErrorEvent](./errorevent/) | Das [`ErrorEvent`](../aspose.svg.dom.events/errorevent/) liefert kontextbezogene Informationen über einen Fehler, der zur Laufzeit aufgetreten ist. |
| [Event](./event/) | Das [`Event`](../aspose.svg.dom.events/event/) wird verwendet, um dem Handler, der das Ereignis verarbeitet, kontextbezogene Informationen über das Ereignis bereitzustellen. |
| [FocusEvent](./focusevent/) | Das FocusEvent-Interface liefert spezifische kontextbezogene Informationen, die mit Fokusereignissen verbunden sind. |
| [InputEvent](./inputevent/) | Eingabeereignisse werden als Benachrichtigungen gesendet, wann immer das DOM aktualisiert wird. |
| [KeyboardEvent](./keyboardevent/) | Das KeyboardEvent-Interface liefert spezifische kontextbezogene Informationen, die mit Tastaturgeräten verbunden sind. Jedes Tastaturereignis verweist über einen Wert auf eine Taste. Tastaturereignisse richten sich in der Regel an das Element, das den Fokus hat. |
| [MouseEvent](./mouseevent/) | Das MouseEvent-Interface liefert spezifische kontextbezogene Informationen, die mit Mausereignissen verbunden sind. |
| [UIEvent](./uievent/) | Das UIEvent-Interface liefert spezifische kontextbezogene Informationen, die mit Benutzeroberflächenereignissen verbunden sind. |
| [WheelEvent](./wheelevent/) | Das WheelEvent-Interface liefert spezifische kontextbezogene Informationen, die mit Radereignissen verbunden sind. Um eine Instanz des WheelEvent-Interface zu erstellen, verwenden Sie den WheelEvent-Konstruktor und übergeben ein optionales WheelEventInit-Wörterbuch. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | Das [`IDocumentEvent`](../aspose.svg.dom.events/idocumentevent/) Interface bietet einen Mechanismus, mit dem der Benutzer ein [`Event`](../aspose.svg.dom.events/event/) eines von der Implementierung unterstützten Typs erstellen kann. |
| [IEventListener](./ieventlistener/) | Das [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) Interface ist die primäre Methode zur Ereignisbehandlung. Benutzer implementieren das [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) Interface und registrieren ihren Listener auf einem [`EventTarget`](../aspose.svg.dom/eventtarget/) mittels der [`AddEventListener`](../aspose.svg.dom/eventtarget/addeventlistener/) Methode. Die Benutzer sollten ihr [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) nach Abschluss der Nutzung ebenfalls von seinem [`EventTarget`](../aspose.svg.dom/eventtarget/) entfernen. |
| [IEventTarget](./ieventtarget/) | Das [`EventTarget`](../aspose.svg.dom/eventtarget/) Interface wird von allen Nodes in einer Implementierung, die das DOM‑Ereignismodell unterstützt, implementiert. Daher kann dieses Interface durch bindungsspezifische Cast‑Methoden auf einer Instanz des Node‑Interfaces erhalten werden. Das Interface ermöglicht die Registrierung und das Entfernen von Event‑Listenern auf einem [`EventTarget`](../aspose.svg.dom/eventtarget/) sowie das Senden von Ereignissen an dieses [`IEventTarget`](../aspose.svg.dom.events/ieventtarget/). |
