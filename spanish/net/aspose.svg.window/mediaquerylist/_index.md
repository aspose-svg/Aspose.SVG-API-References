---
title: "Clase MediaQueryList"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Clase Aspose.Svg.Window.MediaQueryList. Un objeto MediaQueryList almacena información sobre una consulta de medios aplicada a un documento con soporte tanto para coincidencia inmediata como basada en eventos contra el estado del documento. Consulte la especificación del módulo de vista CSSOM https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs
weight: 5960
url: /es/net/aspose.svg.window/mediaquerylist/
---
## MediaQueryList class

Un objeto MediaQueryList almacena información sobre una consulta de medios aplicada a un documento, con soporte tanto para coincidencia inmediata como basada en eventos contra el estado del documento. Consulte la especificación del módulo de vista CSSOM: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```csharp
public class MediaQueryList : EventTarget
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Document](../../aspose.svg.window/mediaquerylist/document/) { get; } | Documento asociado al objeto Context. |
| [Matches](../../aspose.svg.window/mediaquerylist/matches/) { get; } | Un valor booleano que devuelve true si el documento coincide actualmente con la lista de consultas de medios, o false en caso contrario. |
| [Media](../../aspose.svg.window/mediaquerylist/media/) { get; } | Una cadena que representa una consulta de medios serializada. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Configura una función que será llamada cada vez que el evento especificado se entregue al objetivo. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Configura una función que será llamada cada vez que el evento especificado se entregue al objetivo. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Configura una función que será llamada cada vez que el evento especificado se entregue al objetivo. |
| [AddListener](../../aspose.svg.window/mediaquerylist/addlistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Agregar escuchador de evento de cambio de estado de coincidencias de MediaQueryList. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | Envía un Evento al [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) especificado, (de forma síncrona) invocando los EventListeners afectados en el orden apropiado. Las reglas normales de procesamiento de eventos (incluyendo la fase de captura y la fase de burbujeo opcional) también se aplican a los eventos enviados manualmente con [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | Realiza tareas definidas por la aplicación asociadas con la liberación, el descarte o el restablecimiento de recursos no administrados. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Este método se utiliza para obtener el tipo de objeto ECMAScript. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Este método permite la eliminación de escuchadores de eventos del objetivo del evento. Si un [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) se elimina de un [`EventTarget`](../../aspose.svg.dom/eventtarget/) mientras está procesando un evento, no será activado por las acciones actuales. Los escuchadores de eventos nunca pueden ser invocados después de ser eliminados. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | Este método permite la eliminación de escuchadores de eventos del objetivo del evento. Si un [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) se elimina de un [`EventTarget`](../../aspose.svg.dom/eventtarget/) mientras está procesando un evento, no será activado por las acciones actuales. Los escuchadores de eventos nunca pueden ser invocados después de ser eliminados. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | Este método permite la eliminación de escuchadores de eventos del objetivo del evento. Si un [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) se elimina de un [`EventTarget`](../../aspose.svg.dom/eventtarget/) mientras está procesando un evento, no será activado por las acciones actuales. Los escuchadores de eventos nunca pueden ser invocados después de ser eliminados. |
| [RemoveListener](../../aspose.svg.window/mediaquerylist/removelistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | Eliminar escuchador de evento de cambio de estado de coincidencias de MediaQueryList. |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [OnChange](../../aspose.svg.window/mediaquerylist/onchange/) | Evento que se dispara en el MediaQueryList cuando cambia el estado de coincidencias. |

### Ver también

* class [EventTarget](../../aspose.svg.dom/eventtarget/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
