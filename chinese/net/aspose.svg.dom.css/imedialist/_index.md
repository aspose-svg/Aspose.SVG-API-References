---
title: "IMediaList 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Css.IMediaList 接口。MediaList 接口提供有序媒体集合的抽象，而不定义或限制该集合的实现方式。空列表等同于包含所有媒体的列表。"
type: docs
weight: 2730
url: /zh/net/aspose.svg.dom.css/imedialist/
---
## IMediaList interface

MediaList 接口提供了有序媒体集合的抽象，而不定义或限制该集合的实现方式。空列表等同于包含媒体 "all" 的列表。

```csharp
public interface IMediaList : IEnumerable<string>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Item](../../aspose.svg.dom.css/imedialist/item/) { get; } | 返回列表中的第 index 项。如果 index 大于或等于列表中媒体的数量，则返回 null。媒体索引。 |
| [Length](../../aspose.svg.dom.css/imedialist/length/) { get; } | 列表中媒体的数量。有效媒体的范围为 0 到 length-1（含）。 |
| [MediaText](../../aspose.svg.dom.css/imedialist/mediatext/) { get; } | 媒体列表的可解析文本表示形式。这是一个以逗号分隔的媒体列表。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AppendMedium](../../aspose.svg.dom.css/imedialist/appendmedium/)(*string*) | 将媒体 newMedium 添加到列表末尾。如果 newMedium 已经存在，则先将其移除。 |
| [DeleteMedium](../../aspose.svg.dom.css/imedialist/deletemedium/)(*string*) | 从列表中删除由 oldMedium 指示的媒体。 |

### 另请参阅

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
