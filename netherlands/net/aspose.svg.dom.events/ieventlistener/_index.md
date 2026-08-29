---
title: "IEventListener Interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Events.IEventListener interface. De IEventListener interface is de primaire methode voor het afhandelen van events. Gebruikers implementeren de IEventListener interface en registreren hun listener op een EventTarget met behulp van de AddEventListener methode. De gebruikers moeten hun IEventListener ook verwijderen van zijn EventTarget nadat ze klaar zijn met het gebruik van de listener."
type: docs
weight: 2950
url: /nl/net/aspose.svg.dom.events/ieventlistener/
---
## IEventListener interface

De `IEventListener` interface is de primaire methode voor het afhandelen van events. Gebruikers implementeren de `IEventListener` interface en registreren hun listener op een [`EventTarget`](../../aspose.svg.dom/eventtarget/) met behulp van de [`AddEventListener`](../../aspose.svg.dom/eventtarget/addeventlistener/) methode. De gebruikers moeten hun `IEventListener` ook verwijderen van zijn [`EventTarget`](../../aspose.svg.dom/eventtarget/) nadat ze klaar zijn met het gebruik van de listener.

```csharp
public interface IEventListener
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [HandleEvent](../../aspose.svg.dom.events/ieventlistener/handleevent/)(*[Event](../event/)*) | Deze methode wordt aangeroepen telkens wanneer een event van het type optreedt waarvoor de `IEventListener` interface is geregistreerd. |

## Opmerkingen

Wanneer een Node wordt gekopieerd met de cloneNode‑methode, worden de Event Listeners die aan de bron‑Node zijn gekoppeld niet aan de gekopieerde Node gekoppeld. Als de gebruiker dezelfde Event Listeners aan de nieuw gemaakte kopie wil toevoegen, moet de gebruiker ze handmatig toevoegen.

### Zie ook

* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
