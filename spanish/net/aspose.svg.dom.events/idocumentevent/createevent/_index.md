---
title: IDocumentEvent.CreateEvent
second_title: Referencia de API de Aspose.SVG para .NET
description: IDocumentEvent método. Crea unEvent de un tipo soportado por la implementación.
type: docs
weight: 10
url: /es/net/aspose.svg.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Crea un[`Event`](../../event/) de un tipo soportado por la implementación.

```csharp
public Event CreateEvent(string eventType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| eventType | String | El parámetro eventType especifica el tipo de[`Event`](../../event/) interfaz a crear.  Si el[`Event`](../../event/)la interfaz especificada es compatible con la implementación, este método devolverá un new [`Event`](../../event/) del tipo de interfaz solicitado. Si el[`Event`](../../event/)debe ser enviado a través del[`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) método el apropiado [`InitEvent`](../../event/initevent/) El método debe llamarse después de la creación para inicializar el[`Event`](../../event/) valores s. |

### Valor_devuelto

El recién creado[`Event`](../../event/)

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: se genera si la implementación no admite el tipo de[`Event`](../../event/) interfaz solicitada |

### Ver también

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* espacio de nombres [Aspose.Svg.Dom.Events](../../idocumentevent/)
* asamblea [Aspose.SVG](../../../)


