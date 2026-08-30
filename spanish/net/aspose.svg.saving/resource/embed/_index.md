---
title: "Resource.Embed"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método Embed de Resource. Inserta este recurso dentro de su padre codificándolo como Base64. El resultado de la codificación se escribirá en OutputUrl."
type: docs
weight: 60
url: /es/net/aspose.svg.saving/resource/embed/
---
## Resource.Embed method

Inserta este recurso dentro de su padre codificándolo como Base64. El resultado de la codificación se escribirá en [`OutputUrl`](../outputurl/).

```csharp
public Resource Embed(ResourceHandlingContext context)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contexto | ResourceHandlingContext | Contexto de manejo de recursos. |

### Valor de retorno

Este recurso para que puedas encadenar llamadas.

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Se lanza si no existe [`ParentResource`](../../resourcehandlingcontext/parentresource/) porque no hay ningún lugar donde incrustar el resultado. |

### Ver también

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
