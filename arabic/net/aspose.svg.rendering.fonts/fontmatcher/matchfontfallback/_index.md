---
title: "FontMatcher.MatchFontFallback"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة MatchFontFallback في FontMatcher. تُستدعى هذه الطريقة إذا لم يتم العثور على خط مناسب في مجلدات البحث عن الخطوط. يجب أن تُعيد خطًا من نوع true type font بناءً على fontMatchingProperties التي يمكنها عرض charCode أو null إذا لم يتوفر مثل هذا الخط"
type: docs
weight: 10
url: /ar/net/aspose.svg.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

يتم استدعاء هذه الطريقة إذا لم يتم العثور على خط مناسب في مجلدات البحث عن الخطوط. يجب أن تُعيد خطًا من النوع الحقيقي بناءً على *fontMatchingProperties* الذي يمكنه عرض *charCode*، أو `null` إذا لم يكن هذا الخط متاحًا.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    int charCode)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | خصائص الخط المتطابق. |
| charCode | Int32 | رمز الحرف الذي سيتم عرضه باستخدام الخط المتطابق. |

### قيمة الإرجاع

مصفوفة بايت تحتوي على بيانات الخطوط أو `null`.

### انظر أيضًا

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* namespace [Aspose.Svg.Rendering.Fonts](../../../aspose.svg.rendering.fonts/)
* assembly [Aspose.SVG](../../../)
