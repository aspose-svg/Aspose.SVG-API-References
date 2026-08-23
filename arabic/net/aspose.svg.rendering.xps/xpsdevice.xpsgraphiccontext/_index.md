---
title: "فئة XpsDevice.XpsGraphicContext"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Rendering.Xps.XpsDeviceXpsGraphicContext فئة. يحتفظ بمعلمات التحكم الرسومية الحالية لجهاز XpsDevice. تحدد هذه المعلمات الإطار العام الذي تنفّذ فيه عمليات الرسوميات"
type: docs
weight: 5130
url: /ar/net/aspose.svg.rendering.xps/xpsdevice.xpsgraphiccontext/
---
## XpsDevice.XpsGraphicContext class

يحتفظ بمعلمات التحكم الرسومية الحالية لجهاز XpsDevice. تحدد هذه المعلمات الإطار العام الذي تنفّذ فيه عمليات الرسوميات.

```csharp
public class XpsGraphicContext : GraphicContext
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [XpsGraphicContext](../../aspose.svg.rendering.xps/xpsdevice.xpsgraphiccontext/.ctor)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.svg.rendering/graphiccontext/characterspacing/) { get; set; } | يضبط أو يحصل على تباعد الأحرف. |
| [CurrentElement](../../aspose.svg.rendering/graphiccontext/currentelement/) { get; } | يحصل على العنصر المعالج الحالي. |
| virtual [FillBrush](../../aspose.svg.rendering/graphiccontext/fillbrush/) { get; set; } | يضبط أو يحصل على كائن الفرشاة المستخدم لملء داخل المسارات. |
| virtual [Font](../../aspose.svg.rendering/graphiccontext/font/) { get; set; } | يضبط أو يحصل على كائن الخط الحقيقي المستخدم لتصيير النص. |
| virtual [FontSize](../../aspose.svg.rendering/graphiccontext/fontsize/) { get; set; } | يضبط أو يحصل على حجم خط النص. |
| virtual [FontStyle](../../aspose.svg.rendering/graphiccontext/fontstyle/) { get; set; } | يضبط أو يحصل على نمط خط النص. |
| virtual [LineCap](../../aspose.svg.rendering/graphiccontext/linecap/) { get; set; } | يضبط أو يحصل على الشيفرة التي تحدد شكل نقاط النهاية لأي مسار مفتوح يتم رسمه. |
| virtual [LineDashOffset](../../aspose.svg.rendering/graphiccontext/linedashoffset/) { get; set; } | يضبط أو يحصل على إزاحة الطور لنمط الخط المتقطع الحالي. |
| virtual [LineDashPattern](../../aspose.svg.rendering/graphiccontext/linedashpattern/) { get; set; } | يضبط أو يحصل على وصف نمط الخط المتقطع الذي سيُستخدم عندما تُرسم المسارات. يمكن تعيينه إلى null أو مصفوفة فارغة لتعطيله. |
| virtual [LineJoin](../../aspose.svg.rendering/graphiccontext/linejoin/) { get; set; } | يضبط أو يحصل على الشيفرة التي تحدد شكل المفاصل بين القطاعات المتصلة لمسار مُرسم. |
| virtual [LineWidth](../../aspose.svg.rendering/graphiccontext/linewidth/) { get; set; } | يضبط أو يحصل على سمك المسارات التي سيتم رسم حدودها. |
| virtual [MiterLimit](../../aspose.svg.rendering/graphiccontext/miterlimit/) { get; set; } | يضبط أو يحصل على الحد الأقصى لطول وصلات الخط المثلثية للمسارات المرسومة. يحد هذا المعامل من طول "الأشواك" التي تُنتج عندما تتقاطع مقاطع الخط بزاويا حادة. |
| virtual [StrokeBrush](../../aspose.svg.rendering/graphiccontext/strokebrush/) { get; set; } | يضبط أو يحصل على كائن الفرشاة المستخدم للمسارات المرسومة. |
| virtual [TextInfo](../../aspose.svg.rendering/graphiccontext/textinfo/) { get; } | يحصل على كائن [`TextInfo`](../../aspose.svg.rendering/textinfo/) الذي يحتوي على معلومات حول النص المُرَسَم. |
| virtual [TransformationMatrix](../../aspose.svg.rendering/graphiccontext/transformationmatrix/) { get; set; } | يضبط أو يحصل على مصفوفة التحويل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Clone](../../aspose.svg.rendering/graphiccontext/clone/)() | ينشئ نسخة جديدة من فئة **GraphicContext** بنفس قيم الخصائص كما في النسخة الموجودة. |
| virtual [Transform](../../aspose.svg.rendering/graphiccontext/transform/)(*[IMatrix](../../aspose.svg.drawing/imatrix/)*) | عدّل مصفوفة التحويل الحالية بضرب المصفوفة المحددة. |

### انظر أيضًا

* class [GraphicContext](../../aspose.svg.rendering/graphiccontext/)
* class [XpsDevice](../xpsdevice/)
* namespace [Aspose.Svg.Rendering.Xps](../../aspose.svg.rendering.xps/)
* assembly [Aspose.SVG](../../)
