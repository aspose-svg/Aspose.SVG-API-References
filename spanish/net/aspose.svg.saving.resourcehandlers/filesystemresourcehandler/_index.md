---
title: "Clase FileSystemResourceHandler"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Clase Aspose.Svg.Saving.ResourceHandlers.FileSystemResourceHandler. Esta clase es una implementación de la clase ResourceHandler diseñada para guardar recursos en el sistema de archivos local"
type: docs
weight: 5720
url: /es/net/aspose.svg.saving.resourcehandlers/filesystemresourcehandler/
---
## FileSystemResourceHandler class

Esta clase es una implementación de la clase [`ResourceHandler`](../resourcehandler/) diseñada para guardar recursos en el sistema de archivos local.

```csharp
public class FileSystemResourceHandler : ResourceHandler
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor_1)(*string*) | Inicializa una nueva instancia de la clase `FileSystemResourceHandler`. |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor)(*[Url](../../aspose.svg/url/)*) | Inicializa una nueva instancia de la clase `FileSystemResourceHandler`. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [HandleResource](../../aspose.svg.saving.resourcehandlers/filesystemresourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Este método es responsable de manejar el recurso. En él puedes guardar el [`Resource`](../../aspose.svg.saving/resource/) en el flujo o incrustarlo en el recurso padre. |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Este método es responsable de manejar la referencia del recurso. En este método, puedes establecer cómo se verá la referencia al recurso que se está manejando. |

### Ver también

* class [ResourceHandler](../resourcehandler/)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
