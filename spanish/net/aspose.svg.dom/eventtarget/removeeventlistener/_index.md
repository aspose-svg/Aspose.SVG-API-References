---
title: EventTarget.RemoveEventListener
second_title: Referencia de API de Aspose.SVG para .NET
description: EventTarget método. Este método permite eliminar detectores de eventos del destino del evento. SiIEventListener se elimina de unEventTarget mientras está procesando un evento no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos.
type: docs
weight: 40
url: /es/net/aspose.svg.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(string, DOMEventHandler, bool) {#removeeventlistener}

Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) se elimina de un[`EventTarget`](../) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| type | String | Especifica el tipo de evento del[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) siendo removido |
| handler | DOMEventHandler | El[`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/) parámetro indica el[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) ser eliminado. |
| useCapture | Boolean | Especifica si el EventListener que se está eliminando se registró como un detector de captura o no. Si un detector se registró dos veces, uno con captura y otro sin captura, cada uno debe eliminarse por separado. La eliminación de un detector de captura no afecta a una versión que no captura del mismo oyente, y viceversa. |

### Ver también

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* espacio de nombres [Aspose.Svg.Dom](../../eventtarget/)
* asamblea [Aspose.SVG](../../../)

---

## RemoveEventListener(string, IEventListener) {#removeeventlistener_1}

Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) se elimina de un[`EventTarget`](../) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| type | String | Especifica el tipo de evento del[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) siendo removido |
| listener | IEventListener | El[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) parámetro indica el[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) ser eliminado. |

### Ver también

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* espacio de nombres [Aspose.Svg.Dom](../../eventtarget/)
* asamblea [Aspose.SVG](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_2}

Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) se elimina de un[`EventTarget`](../) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| type | String | Especifica el tipo de evento del[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) siendo removido |
| listener | IEventListener | El[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) parámetro indica el[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) ser eliminado. |
| useCapture | Boolean | Especifica si el EventListener que se está eliminando se registró como un detector de captura o no. Si un detector se registró dos veces, uno con captura y otro sin captura, cada uno debe eliminarse por separado. La eliminación de un detector de captura no afecta a una versión que no captura del mismo oyente, y viceversa. |

### Ver también

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* espacio de nombres [Aspose.Svg.Dom](../../eventtarget/)
* asamblea [Aspose.SVG](../../../)


