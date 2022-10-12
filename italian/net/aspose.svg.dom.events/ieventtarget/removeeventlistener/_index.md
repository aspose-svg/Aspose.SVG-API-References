---
title: RemoveEventListener
second_title: Riferimento API Aspose.SVG per .NET
description: Questo metodo consente la rimozione di listener di eventi dalla destinazione dellevento. Se unIEventListeneraspose.svg.dom.events/ieventlistener viene rimosso da unEventTargetaspose.svg.dom/eventtarget mentre sta elaborando un evento non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi.
type: docs
weight: 30
url: /it/net/aspose.svg.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(string, IEventListener) {#removeeventlistener}

Questo metodo consente la rimozione di listener di eventi dalla destinazione dell'evento. Se un[`IEventListener`](../../ieventlistener) viene rimosso da un[`EventTarget`](../../../aspose.svg.dom/eventtarget) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | String | Specifica il tipo di evento di[`IEventListener`](../../ieventlistener) essere rimosso. |
| listener | IEventListener | Il[`IEventListener`](../../ieventlistener) parametro indica il[`IEventListener`](../../ieventlistener) essere rimosso. |

### Guarda anche

* interface [IEventListener](../../ieventlistener)
* interface [IEventTarget](../../ieventtarget)
* spazio dei nomi [Aspose.Svg.Dom.Events](../../ieventtarget)
* assemblea [Aspose.SVG](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_1}

Questo metodo consente la rimozione di listener di eventi dalla destinazione dell'evento. Se un[`IEventListener`](../../ieventlistener) viene rimosso da un[`EventTarget`](../../../aspose.svg.dom/eventtarget) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | String | Specifica il tipo di evento di[`IEventListener`](../../ieventlistener) essere rimosso. |
| listener | IEventListener | Il[`IEventListener`](../../ieventlistener) parametro indica il[`IEventListener`](../../ieventlistener) essere rimosso. |
| useCapture | Boolean | Specifica se EventListener rimosso è stato registrato come listener di acquisizione o meno. Se un listener è stato registrato due volte, uno con acquisizione e uno senza, ciascuno deve essere rimosso separatamente. La rimozione di un listener in acquisizione non influisce su una versione non in acquisizione dello stesso ascoltatore e viceversa. |

### Guarda anche

* interface [IEventListener](../../ieventlistener)
* interface [IEventTarget](../../ieventtarget)
* spazio dei nomi [Aspose.Svg.Dom.Events](../../ieventtarget)
* assemblea [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->