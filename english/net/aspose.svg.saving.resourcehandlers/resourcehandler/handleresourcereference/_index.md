---
title: ResourceHandler.HandleResourceReference
second_title: Aspose.SVG for .NET API Reference
description: ResourceHandler method. This method is responsible for handling the resource reference. In this method you can set what the reference to the resource being handled will look like
type: docs
weight: 20
url: /net/aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

This method is responsible for handling the resource reference. In this method, you can set what the reference to the resource being handled will look like.

```csharp
public virtual string HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resource | Resource | The [`Resource`](../../../aspose.svg.saving/resource/) which will be handled. |
| context | ResourceHandlingContext | Resource handling context. |

### Return Value

A string that will be written to the parent resource and which represents a reference to the resource that is currently being handled.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Raised if [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) is `null` and [`Status`](../../../aspose.svg.saving/resource/status/) is Saved. [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) should be specified for saved resource because otherwise it is impossible to specify the correct reference in the resources referencing this one. |

### See Also

* class [Resource](../../../aspose.svg.saving/resource/)
* class [ResourceHandlingContext](../../../aspose.svg.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../../)
