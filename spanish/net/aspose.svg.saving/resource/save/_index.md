---
title: "Resource.Save"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método Save de Resource. Guarda el recurso en el flujo proporcionado."
type: docs
weight: 70
url: /es/net/aspose.svg.saving/resource/save/
---
## Resource.Save method

Guarda el recurso en el flujo proporcionado.

```csharp
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo en el que se guardará el recurso. |
| contexto | ResourceHandlingContext | Contexto de manejo de recursos. |

### Valor de retorno

Este recurso para que puedas encadenar llamadas.

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Se lanza si [`OutputUrl`](../outputurl/) es `null`. [`OutputUrl`](../outputurl/) debe especificarse antes de guardar el recurso porque de lo contrario es imposible indicar la referencia correcta en los recursos que hacen referencia a este. |

### Ver también

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
