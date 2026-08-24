---
title: "PaintOrder 枚举"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.PaintOrder 枚举。指定在 SVG 元素上应用填充、描边和标记的顺序。"
type: docs
weight: 990
url: /zh/net/aspose.svg.builder/paintorder/
---
## PaintOrder enumeration

指定在 SVG 元素上应用 fill、stroke 和标记的顺序。

```csharp
public enum PaintOrder
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Normal | `0` | 默认绘制顺序：首先填充，然后描边，最后标记。 |
| Fill | `1` | 仅绘制填充。 |
| Stroke | `2` | 仅绘制描边。 |
| Markers | `3` | 仅绘制标记。 |
| FillStroke | `4` | 按顺序绘制：填充，然后描边。 |
| FillMarkers | `5` | 按顺序绘制：填充，然后标记。 |
| StrokeFill | `6` | 按顺序绘制：描边，然后填充。 |
| StrokeMarkers | `7` | 按顺序绘制：描边，然后标记。 |
| MarkersFill | `8` | 按顺序绘制：标记，然后填充。 |
| MarkersStroke | `9` | 按顺序绘制：标记，然后描边。 |
| FillStrokeMarkers | `10` | 按顺序绘制：填充，然后描边，最后标记。 |
| FillMarkersStroke | `11` | 按顺序绘制：填充，然后标记，最后描边。 |
| StrokeFillMarkers | `12` | 按顺序绘制：描边，然后填充，最后标记。 |
| StrokeMarkersFill | `13` | 按顺序绘制：描边，然后标记，最后填充。 |
| MarkersFillStroke | `14` | 按顺序绘制：标记，然后填充，最后描边。 |
| MarkersStrokeFill | `15` | 按顺序绘制标记、描边，最后填充。 |

### 另请参阅

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
