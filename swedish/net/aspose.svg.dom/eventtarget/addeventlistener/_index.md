---
title: "EventTarget.AddEventListener"
second_title: "Aspose.SVG för .NET API-referens"
description: "EventTarget AddEventListener-metoden. Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet."
type: docs
weight: 20
url: /sv/net/aspose.svg.dom/eventtarget/addeventlistener/
---
## AddEventListener(*string, [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/), bool*) {#addeventlistener}

Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet.

Den fungerar genom att lägga till en funktion eller ett objekt som implementerar [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) i listan över händelselyssnare för den angivna händelsetypen på det [`EventTarget`](../) där den anropas. Om funktionen eller objektet redan finns i listan över händelselyssnare för detta mål, läggs de inte till en andra gång.

```csharp
public void AddEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Händelsetypen som användaren registrerar för |
| handler | DOMEventHandler | Tar emot en [`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/) som ska anropas när händelsen inträffar. |
| useCapture | Boolean | Om true indikerar useCapture att användaren vill initiera fångst. Efter att fångst har initierats kommer alla händelser av den angivna typen att skickas till den registrerade [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) innan de skickas till några Event Targets under dem i trädet. Händelser som bubblar uppåt genom trädet kommer inte att trigga en [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) som är avsedd att använda fångst. |

## Anmärkningar

Om en [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) läggs till på ett [`EventTarget`](../) medan det bearbetar ett evenemang, kommer den inte att utlösas av de aktuella åtgärderna men kan utlösas under ett senare steg i händelseflödet, såsom bubblningsfasen.

Om flera identiska Event Listeners registreras på samma [`EventTarget`](../) med samma parametrar så förkastas de duplicerade instanserna. De får inte [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) att anropas två gånger och eftersom de förkastas behöver de inte tas bort med metoden [`RemoveEventListener`](../removeeventlistener/).

### Se även

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)*) {#addeventlistener_1}

Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet.

Den fungerar genom att lägga till en funktion eller ett objekt som implementerar [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) i listan över händelselyssnare för den angivna händelsetypen på det [`EventTarget`](../) där den anropas. Om funktionen eller objektet redan finns i listan över händelselyssnare för detta mål, läggs de inte till en andra gång.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Händelsetypen som användaren registrerar för |
| lyssnare | IEventListener | Tar ett gränssnitt som implementeras av användaren och som innehåller de metoder som ska anropas när händelsen inträffar. |

## Anmärkningar

Om en [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) läggs till på ett [`EventTarget`](../) medan det bearbetar ett evenemang, kommer den inte att utlösas av de aktuella åtgärderna men kan utlösas under ett senare steg i händelseflödet, såsom bubblningsfasen.

Om flera identiska Event Listeners registreras på samma [`EventTarget`](../) med samma parametrar så förkastas de duplicerade instanserna. De får inte [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) att anropas två gånger och eftersom de förkastas behöver de inte tas bort med metoden [`RemoveEventListener`](../removeeventlistener/).

### Se även

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/), bool*) {#addeventlistener_2}

Ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet.

Den fungerar genom att lägga till en funktion eller ett objekt som implementerar [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) i listan över händelselyssnare för den angivna händelsetypen på det [`EventTarget`](../) där den anropas. Om funktionen eller objektet redan finns i listan över händelselyssnare för detta mål, läggs de inte till en andra gång.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Händelsetypen som användaren registrerar för |
| lyssnare | IEventListener | Tar ett gränssnitt som implementeras av användaren och som innehåller de metoder som ska anropas när händelsen inträffar. |
| useCapture | Boolean | Om true indikerar useCapture att användaren vill initiera fångst. Efter att fångst har initierats kommer alla händelser av den angivna typen att skickas till den registrerade [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) innan de skickas till några Event Targets under dem i trädet. Händelser som bubblar uppåt genom trädet kommer inte att trigga en [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) som är avsedd att använda fångst. |

## Anmärkningar

Om en [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) läggs till på ett [`EventTarget`](../) medan det bearbetar ett evenemang, kommer den inte att utlösas av de aktuella åtgärderna men kan utlösas under ett senare steg i händelseflödet, såsom bubblningsfasen.

Om flera identiska Event Listeners registreras på samma [`EventTarget`](../) med samma parametrar så förkastas de duplicerade instanserna. De får inte [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) att anropas två gånger och eftersom de förkastas behöver de inte tas bort med metoden [`RemoveEventListener`](../removeeventlistener/).

### Se även

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
