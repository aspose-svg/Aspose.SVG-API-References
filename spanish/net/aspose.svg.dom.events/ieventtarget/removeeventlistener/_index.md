---
title: IEventTarget.RemoveEventListener
second_title: Referencia de API de Aspose.SVG para .NET
description: IEventTarget método. Este método permite eliminar detectores de eventos del destino del evento. SiIEventListener se elimina de unEventTarget mientras está procesando un evento no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos.
type: docs
weight: 30
url: /es/net/aspose.svg.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(string, IEventListener) {#removeeventlistener}

Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../ieventlistener/) se elimina de un[`EventTarget`](../../../aspose.svg.dom/eventtarget/) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| type | String | Especifica el tipo de evento del[`IEventListener`](../../ieventlistener/) siendo removido |
| listener | IEventListener | El[`IEventListener`](../../ieventlistener/) parámetro indica el[`IEventListener`](../../ieventlistener/) ser eliminado. |

### Ver también

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* espacio de nombres [Aspose.Svg.Dom.Events](../../ieventtarget/)
* asamblea [Aspose.SVG](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_1}

Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../ieventlistener/) se elimina de un[`EventTarget`](../../../aspose.svg.dom/eventtarget/) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| type | String | Especifica el tipo de evento del[`IEventListener`](../../ieventlistener/) siendo removido |
| listener | IEventListener | El[`IEventListener`](../../ieventlistener/) parámetro indica el[`IEventListener`](../../ieventlistener/) ser eliminado. |
| useCapture | Boolean | Especifica si el EventListener que se está eliminando se registró como un detector de captura o no. Si un detector se registró dos veces, uno con captura y otro sin captura, cada uno debe eliminarse por separado. La eliminación de un detector de captura no afecta a una versión que no captura del mismo oyente, y viceversa. |

### Ver también

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* espacio de nombres [Aspose.Svg.Dom.Events](../../ieventtarget/)
* asamblea [Aspose.SVG](../../../)


