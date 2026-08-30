---
title: "ResourceHandler.HandleResourceReference"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método ResourceHandler HandleResourceReference. Este método es responsable de manejar la referencia al recurso. En este método puedes establecer cómo se verá la referencia al recurso que se está manejando."
type: docs
weight: 20
url: /es/net/aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Este método es responsable de manejar la referencia del recurso. En este método, puedes establecer cómo se verá la referencia al recurso que se está manejando.

```csharp
public virtual string HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resource | Resource | El [`Resource`](../../../aspose.svg.saving/resource/) que será manejado. |
| contexto | ResourceHandlingContext | Contexto de manejo de recursos. |

### Valor de retorno

Una cadena que se escribirá en el recurso padre y que representa una referencia al recurso que se está manejando actualmente.

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Se lanza si [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) es `null` y [`Status`](../../../aspose.svg.saving/resource/status/) está Guardado. [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) debe especificarse para el recurso guardado porque de lo contrario es imposible especificar la referencia correcta en los recursos que hacen referencia a este. |

### Ver también

* class [Resource](../../../aspose.svg.saving/resource/)
* class [ResourceHandlingContext](../../../aspose.svg.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../../)
