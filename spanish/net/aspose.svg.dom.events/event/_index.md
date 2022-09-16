---
title: Event
second_title: Referencia de API de Aspose.SVG para .NET
description: ElEvent./event se utiliza para proporcionar información contextual sobre un evento al controlador que procesa el evento.
type: docs
weight: 920
url: /es/net/aspose.svg.dom.events/event/
---
## Event class

El[`Event`](../event) se utiliza para proporcionar información contextual sobre un evento al controlador que procesa el evento.

```csharp
public class Event : DOMObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Event](event#constructor)(string) | Inicializa una nueva instancia del[`Event`](../event) clase. |
| [Event](event#constructor_1)(string, IDictionary&lt;string, object&gt;) | Inicializa una nueva instancia del[`Event`](../event) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles) { get; } | Se utiliza para indicar si un evento es un evento burbujeante o no. Si el evento puede burbujear, el valor es verdadero; de lo contrario, el valor es falso. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable) { get; } | Se utiliza para indicar si un evento puede o no tener su acción predeterminada prevenida. Si se puede evitar la acción predeterminada, el valor es verdadero; de lo contrario, el valor es falso. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget) { get; } | Se utiliza para indicar el[`IEventTarget`](../ieventtarget) cuyo[`IEventListener`](../ieventlistener) los mensajes de correo electrónico se están procesando actualmente. Esto es especialmente útil durante la captura y el burbujeo. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented) { get; } | Devuelve verdadero si se invocó preventDefault() mientras el valor del atributo cancelable es verdadero y falso en caso contrario. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase) { get; } | Se utiliza para indicar qué fase del flujo de eventos se está evaluando actualmente. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted) { get; } | El atributo isTrusted debe devolver el valor con el que se inicializó. Cuando se crea un evento, el atributo debe inicializarse en false. |
| [Target](../../aspose.svg.dom.events/event/target) { get; } | Se utiliza para indicar el[`IEventTarget`](../ieventtarget) al que se despachó originalmente el evento. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp) { get; } | Se utiliza para especificar la hora (en milisegundos con respecto a la época) en la que se creó el evento. Debido al hecho de que algunos sistemas pueden no proporcionar esta información, es posible que el valor de timeStamp no esté disponible para todos los eventos. Cuando no está disponible , se devolverá un valor de 0. Ejemplos de tiempo de época son el tiempo de inicio del sistema o 0:0:0 UTC del 1 de enero de 1970. |
| [Type](../../aspose.svg.dom.events/event/type) { get; } | El nombre del evento (no distingue entre mayúsculas y minúsculas). El nombre debe ser un nombre XML. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent)(string, bool, bool) | El[`InitEvent`](./initevent) El método se utiliza para inicializar el valor de un[`Event`](../event) creado a través de the [`IDocumentEvent`](../idocumentevent) interfaz. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault)() | Si un evento es cancelable, el[`PreventDefault`](./preventdefault) El método se utiliza para indicar que el evento debe cancelarse, lo que significa que no se producirá ninguna acción predeterminada que normalmente toma la implementación como resultado del evento. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation)() | La invocación de este método evita que el evento llegue a cualquier detector de eventos registrado después del actual y, cuando se distribuye en un árbol, también evita que el evento llegue a cualquier otro objeto. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation)() | El[`StopPropagation`](./stoppropagation) El método se utiliza para evitar la propagación adicional de un evento durante el flujo del evento. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [AtTargetPhase](../../aspose.svg.dom.events/event/attargetphase) | La fase de evento actual es la fase de captura. |
| const [BubblingPhase](../../aspose.svg.dom.events/event/bubblingphase) | La fase de evento actual es la fase burbujeante. |
| const [CapturingPhase](../../aspose.svg.dom.events/event/capturingphase) | El evento se está evaluando actualmente en el destino[`IEventTarget`](../ieventtarget) . |
| const [NonePhase](../../aspose.svg.dom.events/event/nonephase) | Los eventos no enviados actualmente están en esta fase. |

### Observaciones

Un objeto que implementa el[`Event`](../event) generalmente se pasa como el primer parámetro a un controlador de eventos. Se pasa información de contexto más específica a los controladores de eventos derivando interfaces adicionales de[`Event`](../event) que contienen información relacionada directamente con el tipo de evento al que acompañan. Estas interfaces derivadas también las implementa el objeto pasado al detector de eventos.

### Ver también

* class [DOMObject](../../aspose.svg.dom/domobject)
* espacio de nombres [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events)
* asamblea [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
