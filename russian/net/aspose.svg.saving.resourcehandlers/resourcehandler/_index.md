---
title: "Класс ResourceHandler"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Saving.ResourceHandlers.ResourceHandler. Этот класс отвечает за обработку ресурсов. Он предоставляет методы, позволяющие контролировать, что будет сделано с ресурсом, а также какую ссылку будет записана в родительский ресурс."
type: docs
weight: 5730
url: /ru/net/aspose.svg.saving.resourcehandlers/resourcehandler/
---
## ResourceHandler class

Этот класс отвечает за обработку ресурсов. Он предоставляет методы, позволяющие контролировать, что будет сделано с [`Resource`](../../aspose.svg.saving/resource/), а также какую ссылку будет записана в родительский [`Resource`](../../aspose.svg.saving/resource/).

```csharp
public abstract class ResourceHandler
```

## Методы

| Имя | Описание |
| --- | --- |
| abstract [HandleResource](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Этот метод отвечает за обработку ресурса. В нём вы можете сохранить [`Resource`](../../aspose.svg.saving/resource/) в поток или встроить его в родительский ресурс. |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Этот метод отвечает за обработку ссылки на ресурс. В этом методе вы можете задать, как будет выглядеть ссылка на обрабатываемый ресурс. |

### См. также

* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
