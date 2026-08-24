---
title: "Location 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Window.Location 类。Location 对象提供其文档浏览上下文中活动文档地址的表示，并允许通过在历史对象中添加或替换条目来更改浏览上下文会话历史的当前条目。"
type: docs
weight: 5950
url: /zh/net/aspose.svg.window/location/
---
## Location class

Location 对象提供其 Document 浏览上下文中活动文档地址的表示，并允许通过在 history 对象中添加或替换条目来更改浏览上下文会话历史的当前条目。

```csharp
public sealed class Location : DOMObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Hash](../../aspose.svg.window/location/hash/) { get; set; } | 返回 Location 对象的 URL 的片段（如果非空则包括前导 "#"）。可以设置，以在更改片段后导航到相同的 URL（忽略前导 "#"）。 |
| [Host](../../aspose.svg.window/location/host/) { get; set; } | 返回 Location 对象的 URL 的主机和端口（如果与方案的默认端口不同）。可以设置，以在更改主机和端口后导航到相同的 URL。 |
| [Hostname](../../aspose.svg.window/location/hostname/) { get; set; } | 返回 Location 对象的 URL 的主机。可以设置，以在更改主机后导航到相同的 URL。 |
| [Href](../../aspose.svg.window/location/href/) { get; set; } | 返回 Location 对象的 URL。可以设置，以导航到给定的 URL。 |
| [Origin](../../aspose.svg.window/location/origin/) { get; } | 返回 Location 对象的 URL 的来源。 |
| [Pathname](../../aspose.svg.window/location/pathname/) { get; set; } | 返回 Location 对象的 URL 的路径。可以设置，以在更改路径后导航到相同的 URL。 |
| [Port](../../aspose.svg.window/location/port/) { get; set; } | 返回 Location 对象的 URL 的端口。可以设置，以在更改端口后导航到相同的 URL。 |
| [Protocol](../../aspose.svg.window/location/protocol/) { get; set; } | 返回 Location 对象的 URL 的方案。可以设置，以在更改方案后导航到相同的 URL。 |
| [Search](../../aspose.svg.window/location/search/) { get; set; } | 返回 Location 对象的 URL 的查询字符串（如果非空则包括前导 "?"）。可以设置，以在更改查询后导航到相同的 URL（忽略前导 "?"）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Assign](../../aspose.svg.window/location/assign/)(*string*) | 导航到给定的页面。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [Reload](../../aspose.svg.window/location/reload/)() | 重新加载当前页面。 |
| [Replace](../../aspose.svg.window/location/replace/)(*string*) | 从会话历史中移除当前页面并导航到给定的页面。 |
| override [ToString](../../aspose.svg.window/location/tostring/)() | 返回 Location 对象的 URL。 |

### 另请参阅

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
