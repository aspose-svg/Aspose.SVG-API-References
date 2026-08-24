---
title: "ResourceHandler 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Saving.ResourceHandlers.ResourceHandler 类。此类负责处理资源。它提供的方法允许您控制对 Resource 的处理方式以及写入父 Resource 的引用。"
type: docs
weight: 5730
url: /zh/net/aspose.svg.saving.resourcehandlers/resourcehandler/
---
## ResourceHandler class

此类负责处理资源。它提供的方法允许您控制对 [`Resource`](../../aspose.svg.saving/resource/) 的处理方式，以及写入父 [`Resource`](../../aspose.svg.saving/resource/) 的引用。

```csharp
public abstract class ResourceHandler
```

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [HandleResource](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | 此方法负责处理资源。在其中您可以将 [`Resource`](../../aspose.svg.saving/resource/) 保存到流中或嵌入到父资源中。 |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | 此方法负责处理资源引用。在此方法中，您可以设置被处理资源的引用应如何显示。 |

### 另请参阅

* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
