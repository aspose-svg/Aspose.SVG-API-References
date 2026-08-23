---
title: "واجهة ITrueTypeFont"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "واجهة Aspose.Svg.Drawing.ITrueTypeFont. تعلن عن طرق للعمل مع خطوط TrueType."
type: docs
weight: 3540
url: /ar/net/aspose.svg.drawing/itruetypefont/
---
## ITrueTypeFont interface

يعلن عن طرق للعمل مع خطوط TrueType.

```csharp
public interface ITrueTypeFont
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DataSize](../../aspose.svg.drawing/itruetypefont/datasize/) { get; } | يحصل على حجم بيانات الخط بالبايت. |
| [FamilyName](../../aspose.svg.drawing/itruetypefont/familyname/) { get; } | يحصل على اسم عائلة الخط. |
| [FullFontName](../../aspose.svg.drawing/itruetypefont/fullfontname/) { get; } | عادةً ما يُمثَّل الاسم الكامل للخط كتركيبة من أسماء العائلة والفرعية. |
| [Style](../../aspose.svg.drawing/itruetypefont/style/) { get; } | احصل على نمط الخط الذي يجمع قيم قاعدة font-face والبيانات من الخط. |
| [SubFamilyName](../../aspose.svg.drawing/itruetypefont/subfamilyname/) { get; } | اسم الفرعية يميز الخط ضمن مجموعة تحمل نفس اسم العائلة. يُفترض أن يُعالج النمط (italic, oblique) والوزن (light, bold, black, إلخ). يجب أن يحتوي الخط الذي لا يختلف في الوزن أو النمط على السلسلة "Regular". |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetAscent](../../aspose.svg.drawing/itruetypefont/getascent/)(*float*) | يحصل على ارتفاع الخط (ascent) بالنقاط باستخدام حجم الخط المحدد. |
| [GetData](../../aspose.svg.drawing/itruetypefont/getdata/)() | يفتح الدفق (stream) ببيانات الخط. المتصل مسؤول عن تحرير الدفق. |
| [GetDescent](../../aspose.svg.drawing/itruetypefont/getdescent/)(*float*) | يحصل على انخفاض الخط (descent) بالنقاط باستخدام حجم الخط المحدد. |

### انظر أيضًا

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
