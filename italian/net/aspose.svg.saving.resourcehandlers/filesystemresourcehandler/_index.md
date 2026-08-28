---
title: "Classe FileSystemResourceHandler"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Saving.ResourceHandlers.FileSystemResourceHandler. Questa classe è un'implementazione della classe ResourceHandler progettata per salvare le risorse sul file system locale"
type: docs
weight: 5720
url: /it/net/aspose.svg.saving.resourcehandlers/filesystemresourcehandler/
---
## FileSystemResourceHandler class

Questa classe è un'implementazione della classe [`ResourceHandler`](../resourcehandler/) progettata per salvare le risorse sul file system locale.

```csharp
public class FileSystemResourceHandler : ResourceHandler
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor_1)(*string*) | Inizializza una nuova istanza della classe `FileSystemResourceHandler`. |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor)(*[Url](../../aspose.svg/url/)*) | Inizializza una nuova istanza della classe `FileSystemResourceHandler`. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [HandleResource](../../aspose.svg.saving.resourcehandlers/filesystemresourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Questo metodo è responsabile della gestione della risorsa. In esso è possibile salvare la [`Resource`](../../aspose.svg.saving/resource/) nello stream o incorporarla nella risorsa padre. |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Questo metodo è responsabile della gestione del riferimento alla risorsa. In questo metodo, è possibile impostare come apparirà il riferimento alla risorsa gestita. |

### Vedi anche

* class [ResourceHandler](../resourcehandler/)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
