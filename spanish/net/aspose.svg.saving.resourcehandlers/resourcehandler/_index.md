---
title: "Clase ResourceHandler"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Clase Aspose.Svg.Saving.ResourceHandlers.ResourceHandler. Esta clase es responsable de manejar recursos. Proporciona métodos que le permiten controlar lo que se hará con el Resource, así como la referencia que se escribirá en el Resource padre."
type: docs
weight: 5730
url: /es/net/aspose.svg.saving.resourcehandlers/resourcehandler/
---
## ResourceHandler class

Esta clase es responsable de manejar recursos. Proporciona métodos que le permiten controlar lo que se hará con el [`Resource`](../../aspose.svg.saving/resource/), así como la referencia que se escribirá en el [`Resource`](../../aspose.svg.saving/resource/) padre.

```csharp
public abstract class ResourceHandler
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| abstract [HandleResource](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Este método es responsable de manejar el recurso. En él puedes guardar el [`Resource`](../../aspose.svg.saving/resource/) en el flujo o incrustarlo en el recurso padre. |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Este método es responsable de manejar la referencia del recurso. En este método, puedes establecer cómo se verá la referencia al recurso que se está manejando. |

### Ver también

* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
