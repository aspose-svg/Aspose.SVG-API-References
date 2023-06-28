---
title: FontMatcher.MatchFontFallback
second_title: Aspose.SVG for .NET API Reference
description: FontMatcher method. This method is called if there is no appropriate font found in the fonts lookup folders. It should return true type font based on the fontMatchingProperties which can render charCode or null if such font is not available
type: docs
weight: 10
url: /net/aspose.svg.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

This method is called if there is no appropriate font found in the fonts lookup folders. It should return true type font based on the *fontMatchingProperties* which can render *charCode*, or `null` if such font is not available.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Properties of the matched font. |
| charCode | UInt32 | Code of the character which will be rendered using the matched font. |

### Return Value

A byte array containing the fonts data or `null`.

### See Also

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* namespace [Aspose.Svg.Rendering.Fonts](../../../aspose.svg.rendering.fonts/)
* assembly [Aspose.SVG](../../../)
