---
title: "ITrueTypeFont 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Drawing.ITrueTypeFont 接口。声明用于处理 TrueType 字体的方法"
type: docs
weight: 3540
url: /zh/net/aspose.svg.drawing/itruetypefont/
---
## ITrueTypeFont interface

声明用于处理 TrueType 字体的方法。

```csharp
public interface ITrueTypeFont
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [DataSize](../../aspose.svg.drawing/itruetypefont/datasize/) { get; } | 获取字体数据的大小（字节）。 |
| [FamilyName](../../aspose.svg.drawing/itruetypefont/familyname/) { get; } | 获取字体族的名称。 |
| [FullFontName](../../aspose.svg.drawing/itruetypefont/fullfontname/) { get; } | 完整字体名称通常表示为族名和子族名的组合。 |
| [Style](../../aspose.svg.drawing/itruetypefont/style/) { get; } | 获取将 font-face 规则的值与字体数据相结合的字体样式。 |
| [SubFamilyName](../../aspose.svg.drawing/itruetypefont/subfamilyname/) { get; } | 子族名称用于区分同一族名组中的字体。它通常用于表示样式（斜体、倾斜）和粗细（细体、粗体、黑体等）。没有特定粗细或样式差异的字体应使用字符串 “Regular”。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetAscent](../../aspose.svg.drawing/itruetypefont/getascent/)(*float*) | 使用指定的字体大小获取字体的上升度（点）。 |
| [GetData](../../aspose.svg.drawing/itruetypefont/getdata/)() | 打开包含字体数据的流。调用方负责释放该流。 |
| [GetDescent](../../aspose.svg.drawing/itruetypefont/getdescent/)(*float*) | 使用指定的字体大小获取字体的下降度（点）。 |

### 另请参阅

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
