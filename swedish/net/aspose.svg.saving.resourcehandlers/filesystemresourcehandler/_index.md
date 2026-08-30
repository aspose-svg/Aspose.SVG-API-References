---
title: "FileSystemResourceHandler‑klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Saving.ResourceHandlers.FileSystemResourceHandler‑klass. Denna klass är en implementation av ResourceHandler‑klassen som är avsedd att spara resurser till det lokala filsystemet."
type: docs
weight: 5720
url: /sv/net/aspose.svg.saving.resourcehandlers/filesystemresourcehandler/
---
## FileSystemResourceHandler class

Denna klass är en implementation av [`ResourceHandler`](../resourcehandler/)‑klassen som är avsedd att spara resurser till det lokala filsystemet.

```csharp
public class FileSystemResourceHandler : ResourceHandler
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor_1)(*string*) | Initierar en ny instans av `FileSystemResourceHandler`‑klassen. |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor)(*[Url](../../aspose.svg/url/)*) | Initierar en ny instans av `FileSystemResourceHandler`‑klassen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [HandleResource](../../aspose.svg.saving.resourcehandlers/filesystemresourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Denna metod ansvarar för att hantera resursen. I den kan du spara [`Resource`](../../aspose.svg.saving/resource/) till strömmen eller bädda in den i föräldraresursen. |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Denna metod ansvarar för att hantera resursreferensen. I denna metod kan du ange hur referensen till den hanterade resursen ska se ut. |

### Se även

* class [ResourceHandler](../resourcehandler/)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
