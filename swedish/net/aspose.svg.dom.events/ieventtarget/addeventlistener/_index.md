---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.SVG för .NET API-referens"
description: "IEventTarget AddEventListener‑metod. Denna metod möjliggör registrering av händelselyssnare på mål‑händelseobjektet."
type: docs
weight: 10
url: /sv/net/aspose.svg.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(*string, [IEventListener](../../ieventlistener/)*) {#addeventlistener}

Denna metod möjliggör registrering av händelselyssnare på händelsemålet.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Händelsetypen som användaren registrerar för |
| lyssnare | IEventListener | Tar ett gränssnitt som implementeras av användaren och som innehåller de metoder som ska anropas när händelsen inträffar. |

## Anmärkningar

Om en [`IEventListener`](../../ieventlistener/) läggs till i ett [`EventTarget`](../../../aspose.svg.dom/eventtarget/) medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna men kan utlösas under ett senare skede av händelseflödet, såsom bubbelfasen.

Om flera identiska händelselyssnare registreras på samma [`EventTarget`](../../../aspose.svg.dom/eventtarget/) med samma parametrar så kasseras de duplicerade instanserna. De får inte [`IEventListener`](../../ieventlistener/) att anropas två gånger och eftersom de kasseras behöver de inte tas bort med metoden [`RemoveEventListener`](../removeeventlistener/).

### Se även

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../ieventlistener/), bool*) {#addeventlistener_1}

Denna metod möjliggör registrering av händelselyssnare på händelsemålet.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Händelsetypen som användaren registrerar för |
| lyssnare | IEventListener | Tar ett gränssnitt som implementeras av användaren och som innehåller de metoder som ska anropas när händelsen inträffar. |
| useCapture | Boolean | Om true, indikerar useCapture att användaren vill initiera capture. Efter att capture har initierats kommer alla händelser av den angivna typen att skickas till den registrerade [`IEventListener`](../../ieventlistener/) innan de skickas till några Event Targets under dem i trädet. Händelser som bubblar upp genom trädet kommer inte att utlösa en [`IEventListener`](../../ieventlistener/) som är avsedd att använda capture. |

## Anmärkningar

Om en [`IEventListener`](../../ieventlistener/) läggs till i ett [`EventTarget`](../../../aspose.svg.dom/eventtarget/) medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna men kan utlösas under ett senare skede av händelseflödet, såsom bubbelfasen.

Om flera identiska händelselyssnare registreras på samma [`EventTarget`](../../../aspose.svg.dom/eventtarget/) med samma parametrar så kasseras de duplicerade instanserna. De får inte [`IEventListener`](../../ieventlistener/) att anropas två gånger och eftersom de kasseras behöver de inte tas bort med metoden [`RemoveEventListener`](../removeeventlistener/).

### Se även

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
