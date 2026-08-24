---
title: "FileSystemResourceHandler 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Saving.ResourceHandlers.FileSystemResourceHandler 类。此类是 ResourceHandler 类的实现，旨在将资源保存到本地文件系统。"
type: docs
weight: 5720
url: /zh/net/aspose.svg.saving.resourcehandlers/filesystemresourcehandler/
---
## FileSystemResourceHandler class

此类是 [`ResourceHandler`](../resourcehandler/) 类的实现，旨在将资源保存到本地文件系统。

```csharp
public class FileSystemResourceHandler : ResourceHandler
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor_1)(*string*) | 初始化 `FileSystemResourceHandler` 类的新实例。 |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor)(*[Url](../../aspose.svg/url/)*) | 初始化 `FileSystemResourceHandler` 类的新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [HandleResource](../../aspose.svg.saving.resourcehandlers/filesystemresourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | 此方法负责处理资源。在其中您可以将 [`Resource`](../../aspose.svg.saving/resource/) 保存到流中或嵌入到父资源中。 |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | 此方法负责处理资源引用。在此方法中，您可以设置被处理资源的引用应如何显示。 |

### 另请参阅

* class [ResourceHandler](../resourcehandler/)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
