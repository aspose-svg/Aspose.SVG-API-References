---
title: "ResourceHandler.HandleResourceReference"
second_title: "Aspose.SVG for .NET API 参考"
description: "ResourceHandler HandleResourceReference 方法。此方法负责处理资源引用。在此方法中，您可以设置被处理资源的引用将如何显示。"
type: docs
weight: 20
url: /zh/net/aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

此方法负责处理资源引用。在此方法中，您可以设置被处理资源的引用应如何显示。

```csharp
public virtual string HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resource | Resource | 将要处理的 [`Resource`](../../../aspose.svg.saving/resource/)。 |
| context | ResourceHandlingContext | 资源处理上下文。 |

### 返回值

一个将写入父资源的字符串，表示当前正在处理的资源的引用。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 如果 [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) 为 `null` 且 [`Status`](../../../aspose.svg.saving/resource/status/) 为 Saved，则会引发此错误。对于已保存的资源应指定 [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/)，否则无法在引用此资源的资源中指定正确的引用。 |

### 另请参阅

* class [Resource](../../../aspose.svg.saving/resource/)
* class [ResourceHandlingContext](../../../aspose.svg.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../../)
