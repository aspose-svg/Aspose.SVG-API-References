---
title: "FontMatcher.MatchFontFallback"
second_title: "Aspose.SVG for .NET API 参考"
description: "FontMatcher MatchFontFallback 方法。此方法在字体查找文件夹中未找到合适的字体时调用。它应根据能够渲染 charCode 的 fontMatchingProperties 返回真实类型的字体，如果没有可用的字体则返回 null"
type: docs
weight: 10
url: /zh/net/aspose.svg.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

如果在字体查找文件夹中未找到合适的字体，将调用此方法。它应根据 *fontMatchingProperties* 返回可渲染 *charCode* 的真字体类型，如果不存在此类字体，则返回 `null`。

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    int charCode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | 匹配字体的属性。 |
| charCode | Int32 | 使用匹配字体渲染的字符的代码。 |

### 返回值

包含字体数据的字节数组或 `null`。

### 另请参阅

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* namespace [Aspose.Svg.Rendering.Fonts](../../../aspose.svg.rendering.fonts/)
* assembly [Aspose.SVG](../../../)
