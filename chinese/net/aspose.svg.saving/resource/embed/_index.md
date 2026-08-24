---
title: "Resource.Embed"
second_title: "Aspose.SVG for .NET API 参考"
description: "Resource Embed 方法。通过将此资源编码为 Base64 并嵌入其父级来嵌入资源。编码结果将写入 OutputUrl"
type: docs
weight: 60
url: /zh/net/aspose.svg.saving/resource/embed/
---
## Resource.Embed method

通过将此资源编码为 Base64 并嵌入其父级来嵌入资源。编码结果将写入 [`OutputUrl`](../outputurl/)。

```csharp
public Resource Embed(ResourceHandlingContext context)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| context | ResourceHandlingContext | 资源处理上下文。 |

### 返回值

此资源，以便您可以进行链式调用。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 如果没有 [`ParentResource`](../../resourcehandlingcontext/parentresource/)，则会抛出此异常，因为没有位置可以嵌入结果。 |

### 另请参阅

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
