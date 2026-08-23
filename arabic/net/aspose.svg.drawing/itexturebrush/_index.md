---
title: "واجهة ITextureBrush"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Drawing.ITextureBrush interface. يعرّف واجهة الفرشاة التي تستخدم صورة لملء داخل الشكل"
type: docs
weight: 3520
url: /ar/net/aspose.svg.drawing/itexturebrush/
---
## ITextureBrush interface

يعرف واجهة فرشاة تستخدم صورة لملء داخل الشكل.

```csharp
public interface ITextureBrush : ITransformableBrush
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ColorMap](../../aspose.svg.drawing/itexturebrush/colormap/) { get; } | يجب أن يكون عدد العناصر زوجيًا. كل عنصر زوجي هو اللون القديم. كل عنصر فردي هو اللون الجديد. |
| [Image](../../aspose.svg.drawing/itexturebrush/image/) { get; } | يحصل أو يضبط الصورة المستخدمة بواسطة الفرشاة. |
| [ImageArea](../../aspose.svg.drawing/itexturebrush/imagearea/) { get; } | يحدد الجزء من الصورة المستخدم بواسطة الفرشاة. إذا كان يساوي RectangleF.Empty فسيتم استخدام الصورة بالكامل. الإحداثيات بوحدات البكسل. |
| [Opacity](../../aspose.svg.drawing/itexturebrush/opacity/) { get; set; } | احصل على قيمة الشفافية في مصفوفة تحويل اللون. |

### انظر أيضًا

* interface [ITransformableBrush](../itransformablebrush/)
* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
