---
title: "ReferrerPolicy 枚举"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.ReferrerPolicy 枚举。指定获取资源时使用的引用策略。"
type: docs
weight: 1020
url: /zh/net/aspose.svg.builder/referrerpolicy/
---
## ReferrerPolicy enumeration

指定获取资源时使用的引用者策略。

```csharp
public enum ReferrerPolicy
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 未设置引用策略。 |
| NoReferrer | `1` | 不会发送 Referer 头。 |
| NoReferrerWhenDowngrade | `2` | 不会向安全性较低的源（HTTPS -> HTTP）发送 Referer 头。 |
| SameOrigin | `3` | 仅在同源请求时发送 Referer 头。 |
| Origin | `4` | 仅将文档的来源作为 Referer 头发送。 |
| StrictOrigin | `5` | 仅在安全上下文中将文档的来源作为 Referer 头发送。 |
| OriginWhenCrossOrigin | `6` | 在同源请求中，完整 URL 将作为 Referer 头发送；跨源请求则仅发送来源。 |
| StrictOriginWhenCrossOrigin | `7` | 在同源请求中，仅将文档的来源作为 Referer 头发送；在不安全的跨源请求中不发送任何头。 |
| UnsafeUrl | `8` | 完整 URL（包括路径和查询字符串）将始终作为 Referer 头发送。 |

### 另请参阅

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
