---
title: RemoveEventListener
second_title: Aspose.SVG för .NET API Referens
description: Denna metod tillåter att händelseavlyssnare tas bort från händelsemålet. Om enIEventListeneraspose.svg.dom.events/ieventlistener tas bort från enEventTargetaspose.svg.dom/eventtarget medan den bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de tagits bort.
type: docs
weight: 40
url: /sv/net/aspose.svg.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(string, DOMEventHandler, bool) {#removeeventlistener}

Denna metod tillåter att händelseavlyssnare tas bort från händelsemålet. Om en[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) tas bort från en[`EventTarget`](../../eventtarget) medan den bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de tagits bort.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Anger händelsetypen för[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) tas bort. |
| handler | DOMEventHandler | De[`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler) parameter indikerar[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) ska tas bort. |
| useCapture | Boolean | Anger om EventListener som tas bort har registrerats som en infångande lyssnare eller inte. Om en lyssnare registrerades två gånger, en med infångning och en utan, måste var och en tas bort separat. Borttagning av en infångande lyssnare påverkar inte en icke-fångande version av samma lyssnare och vice versa. |

### Se även

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler)
* class [EventTarget](../../eventtarget)
* namnutrymme [Aspose.Svg.Dom](../../eventtarget)
* hopsättning [Aspose.SVG](../../../)

---

## RemoveEventListener(string, IEventListener) {#removeeventlistener_1}

Denna metod tillåter att händelseavlyssnare tas bort från händelsemålet. Om en[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) tas bort från en[`EventTarget`](../../eventtarget) medan den bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de tagits bort.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Anger händelsetypen för[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) tas bort. |
| listener | IEventListener | De[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) parameter indikerar[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) ska tas bort. |

### Se även

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener)
* class [EventTarget](../../eventtarget)
* namnutrymme [Aspose.Svg.Dom](../../eventtarget)
* hopsättning [Aspose.SVG](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_2}

Denna metod tillåter att händelseavlyssnare tas bort från händelsemålet. Om en[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) tas bort från en[`EventTarget`](../../eventtarget) medan den bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de tagits bort.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Anger händelsetypen för[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) tas bort. |
| listener | IEventListener | De[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) parameter indikerar[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) ska tas bort. |
| useCapture | Boolean | Anger om EventListener som tas bort har registrerats som en infångande lyssnare eller inte. Om en lyssnare registrerades två gånger, en med infångning och en utan, måste var och en tas bort separat. Borttagning av en infångande lyssnare påverkar inte en icke-fångande version av samma lyssnare och vice versa. |

### Se även

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener)
* class [EventTarget](../../eventtarget)
* namnutrymme [Aspose.Svg.Dom](../../eventtarget)
* hopsättning [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->