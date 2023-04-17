---
title: Event.StopPropagation
second_title: Referencia de API de Aspose.SVG para .NET
description: Event método. ElStopPropagation El método se utiliza para evitar la propagación adicional de un evento durante el flujo del evento.
type: docs
weight: 140
url: /es/net/aspose.svg.dom.events/event/stoppropagation/
---
## Event.StopPropagation method

El`StopPropagation` El método se utiliza para evitar la propagación adicional de un evento durante el flujo del evento.

```csharp
public void StopPropagation()
```

### Observaciones

Si este método es llamado por cualquier[`IEventListener`](../../ieventlistener/) el evento dejará de propagarse a través del árbol. El evento completará el envío a todos los oyentes en el actual[`IEventTarget`](../../ieventtarget/) antes de que se detenga el flujo de eventos. Este método se puede utilizar durante cualquier etapa del flujo de eventos.

### Ver también

* class [Event](../)
* espacio de nombres [Aspose.Svg.Dom.Events](../../event/)
* asamblea [Aspose.SVG](../../../)


