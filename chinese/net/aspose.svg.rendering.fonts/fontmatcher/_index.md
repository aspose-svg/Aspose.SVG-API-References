---
title: "FontMatcher 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Rendering.Fonts.FontMatcher 类。此类允许您控制字体匹配算法的某些部分。"
type: docs
weight: 4850
url: /zh/net/aspose.svg.rendering.fonts/fontmatcher/
---
## FontMatcher class

此类允许您控制字体匹配算法的某些部分。

```csharp
public abstract class FontMatcher
```

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [MatchFontFallback](../../aspose.svg.rendering.fonts/fontmatcher/matchfontfallback/)(*[FontMatchingProperties](../fontmatchingproperties/), int*) | 如果在字体查找文件夹中未找到合适的字体，将调用此方法。它应根据 *fontMatchingProperties* 返回可渲染 *charCode* 的真字体类型，如果不存在此类字体，则返回 `null`。 |

### 另请参阅

* namespace [Aspose.Svg.Rendering.Fonts](../../aspose.svg.rendering.fonts/)
* assembly [Aspose.SVG](../../)
