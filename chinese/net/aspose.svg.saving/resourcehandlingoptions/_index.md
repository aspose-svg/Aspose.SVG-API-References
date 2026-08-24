---
title: "ResourceHandlingOptions 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Saving.ResourceHandlingOptions 类。表示资源处理选项"
type: docs
weight: 5760
url: /zh/net/aspose.svg.saving/resourcehandlingoptions/
---
## ResourceHandlingOptions class

表示资源处理选项。

```csharp
public class ResourceHandlingOptions
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Default](../../aspose.svg.saving/resourcehandlingoptions/default/) { get; set; } | 获取或设置表示资源处理默认方式的枚举。目前支持 Save、Ignore 和 Embed 值。默认值为 Save。 |
| [JavaScript](../../aspose.svg.saving/resourcehandlingoptions/javascript/) { get; set; } | 获取或设置表示脚本处理方式的枚举。目前支持 Save、Ignore、Discard 和 Embed 值。默认值为 Save。 |
| [MaxHandlingDepth](../../aspose.svg.saving/resourcehandlingoptions/maxhandlingdepth/) { get; set; } | 获取或设置将要处理的页面的最大深度。深度为 1 表示仅处理直接从已保存文档引用的页面。将此属性设置为 -1 将处理所有页面。默认值为 0。 |
| [PageUrlRestriction](../../aspose.svg.saving/resourcehandlingoptions/pageurlrestriction/) { get; set; } | 获取或设置对已处理页面的 URL 应用的限制。默认值为 RootAndSubFolders。 |
| [ResourceUrlRestriction](../../aspose.svg.saving/resourcehandlingoptions/resourceurlrestriction/) { get; set; } | 获取或设置对已处理资源（如 css、js、图像等）的 URL 应用的限制。默认值为 SameHost。 |

### 另请参阅

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
