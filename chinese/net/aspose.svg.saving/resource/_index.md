---
title: "Resource 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Saving.Resource 类。此类描述资源并提供处理资源的方法。"
type: docs
weight: 5710
url: /zh/net/aspose.svg.saving/resource/
---
## Resource class

此类描述资源并提供处理该资源的方法。

```csharp
public class Resource
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [MimeType](../../aspose.svg.saving/resource/mimetype/) { get; } | 返回此资源的 !:Html.MimeType。如果未找到资源，则可能为 `null`。 |
| [OriginalReference](../../aspose.svg.saving/resource/originalreference/) { get; } | 返回一个包含此资源原始引用的字符串。 |
| [OriginalUrl](../../aspose.svg.saving/resource/originalurl/) { get; } | 返回指示此资源所在位置的 URL。 |
| [OutputUrl](../../aspose.svg.saving/resource/outputurl/) { get; set; } | 获取或设置指示资源在处理后将位于何处的 URL。 |
| [Status](../../aspose.svg.saving/resource/status/) { get; } | 返回资源的当前状态。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Embed](../../aspose.svg.saving/resource/embed/)(*[ResourceHandlingContext](../resourcehandlingcontext/)*) | 通过将此资源编码为 Base64 并嵌入其父级来实现。编码结果将写入 [`OutputUrl`](./outputurl/)。 |
| [Save](../../aspose.svg.saving/resource/save/)(*Stream, [ResourceHandlingContext](../resourcehandlingcontext/)*) | 将资源保存到提供的流中。 |
| [WithOutputUrl](../../aspose.svg.saving/resource/withoutputurl/)(*[Url](../../aspose.svg/url/)*) | 指定指示资源在处理后将位于何处的新 URL。 |

### 另请参阅

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
