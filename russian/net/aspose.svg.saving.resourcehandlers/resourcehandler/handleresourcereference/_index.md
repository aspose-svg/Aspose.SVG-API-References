---
title: "ResourceHandler.HandleResourceReference"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод ResourceHandler HandleResourceReference. Этот метод отвечает за обработку ссылки на ресурс. В этом методе вы можете задать, как будет выглядеть ссылка на обрабатываемый ресурс."
type: docs
weight: 20
url: /ru/net/aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Этот метод отвечает за обработку ссылки на ресурс. В этом методе вы можете задать, как будет выглядеть ссылка на обрабатываемый ресурс.

```csharp
public virtual string HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| resource | Resource | [`Resource`](../../../aspose.svg.saving/resource/), который будет обработан. |
| context | ResourceHandlingContext | Контекст обработки ресурса. |

### Возвращаемое значение

Строка, которая будет записана в родительский ресурс и представляет собой ссылку на ресурс, который в данный момент обрабатывается.

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Вызывается, если [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) имеет значение `null` и [`Status`](../../../aspose.svg.saving/resource/status/) равен Saved. [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) должен быть указан для сохранённого ресурса, иначе невозможно указать правильную ссылку в ресурсах, ссылающихся на этот. |

### См. также

* class [Resource](../../../aspose.svg.saving/resource/)
* class [ResourceHandlingContext](../../../aspose.svg.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../../)
