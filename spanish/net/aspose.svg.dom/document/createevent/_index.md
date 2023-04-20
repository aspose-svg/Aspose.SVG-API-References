---
title: Document.CreateEvent
second_title: Referencia de API de Aspose.SVG para .NET
description: Document método. Crea unEvent de un tipo soportado por la implementación.
type: docs
weight: 880
url: /es/net/aspose.svg.dom/document/createevent/
---
## Document.CreateEvent method

Crea un[`Event`](../../../aspose.svg.dom.events/event/) de un tipo soportado por la implementación.

```csharp
public Event CreateEvent(string eventType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| eventType | String | El parámetro eventType especifica el tipo de[`Event`](../../../aspose.svg.dom.events/event/) interfaz a crear.  Si el[`Event`](../../../aspose.svg.dom.events/event/) interfaz especificada es compatible con la implementación de este método will devolverá un nuevo[`Event`](../../../aspose.svg.dom.events/event/) del tipo de interfaz solicitado. Si el[`Event`](../../../aspose.svg.dom.events/event/)debe ser enviado a través del[`DispatchEvent`](../../../aspose.svg.dom.events/ieventtarget/dispatchevent/) método el apropiado[`InitEvent`](../../../aspose.svg.dom.events/event/initevent/) El método debe llamarse después de la creación para inicializar el[`Event`](../../../aspose.svg.dom.events/event/) valores s. |

### Valor_devuelto

El recién creado[`Event`](../../../aspose.svg.dom.events/event/)

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: se genera si la implementación no admite el tipo de[`Event`](../../../aspose.svg.dom.events/event/) interfaz solicitada |

### Ver también

* class [Event](../../../aspose.svg.dom.events/event/)
* class [Document](../)
* espacio de nombres [Aspose.Svg.Dom](../../document/)
* asamblea [Aspose.SVG](../../../)


