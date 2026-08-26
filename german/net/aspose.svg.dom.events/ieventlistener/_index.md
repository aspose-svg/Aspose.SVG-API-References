---
title: "IEventListener Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Events.IEventListener Schnittstelle. Die IEventListener‑Schnittstelle ist die primäre Methode zur Ereignisbehandlung. Benutzer implementieren die IEventListener‑Schnittstelle und registrieren ihren Listener auf einem EventTarget mittels der AddEventListener‑Methode. Die Benutzer sollten ihren IEventListener nach Abschluss der Nutzung vom EventTarget entfernen."
type: docs
weight: 2950
url: /de/net/aspose.svg.dom.events/ieventlistener/
---
## IEventListener interface

Die `IEventListener`-Schnittstelle ist die primäre Methode zur Behandlung von Ereignissen. Benutzer implementieren die `IEventListener`-Schnittstelle und registrieren ihren Listener auf einem [`EventTarget`](../../aspose.svg.dom/eventtarget/) mithilfe der [`AddEventListener`](../../aspose.svg.dom/eventtarget/addeventlistener/)‑Methode. Die Benutzer sollten ihren `IEventListener` auch von seinem [`EventTarget`](../../aspose.svg.dom/eventtarget/) entfernen, nachdem sie den Listener nicht mehr benötigen.

```csharp
public interface IEventListener
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [HandleEvent](../../aspose.svg.dom.events/ieventlistener/handleevent/)(*[Event](../event/)*) | Diese Methode wird aufgerufen, sobald ein Ereignis des Typs auftritt, für den die `IEventListener`-Schnittstelle registriert wurde. |

## Hinweise

Wenn ein Knoten mit der cloneNode‑Methode kopiert wird, werden die an den Quellknoten angehängten Event‑Listener nicht an den kopierten Knoten angehängt. Wenn der Benutzer dieselben Event‑Listener zum neu erstellten Kopie hinzufügen möchte, muss er sie manuell hinzufügen.

### Siehe auch

* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
