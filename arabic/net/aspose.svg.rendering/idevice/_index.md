---
title: "واجهة IDevice"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Rendering.IDevice interface. يعرّف الأساليب والخصائص التي تدعم التصيير المخصص لعناصر الرسوم مثل المسارات والنصوص والصور"
type: docs
weight: 4890
url: /ar/net/aspose.svg.rendering/idevice/
---
## IDevice interface

يعرّف الطرق والخصائص التي تدعم عرضًا مخصصًا لعناصر الرسوم مثل المسارات والنصوص والصور.

```csharp
public interface IDevice : IDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/idevice/graphiccontext/) { get; } | يحصل على سياق الرسوم. |
| [Options](../../aspose.svg.rendering/idevice/options/) { get; } | يحصل على خيارات التصيير. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddRect](../../aspose.svg.rendering/idevice/addrect/)(*RectangleF*) | يضيف مستطيلًا إلى المسار الحالي كمسار فرعي كامل. |
| [BeginDocument](../../aspose.svg.rendering/idevice/begindocument/)(*[Document](../../aspose.svg.dom/document/)*) | يبدأ تصيير المستند. |
| [BeginElement](../../aspose.svg.rendering/idevice/beginelement/)(*[Element](../../aspose.svg.dom/element/), RectangleF*) | يبدأ تصيير العنصر. |
| [BeginPage](../../aspose.svg.rendering/idevice/beginpage/)(*SizeF*) | يبدأ تصيير الصفحة الجديدة. |
| [Clip](../../aspose.svg.rendering/idevice/clip/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | يعدّل مسار القص الحالي عن طريق تقاطعه مع المسار الحالي، باستخدام FillRule لتحديد المنطقة التي يجب ملؤها. تنهي هذه الطريقة المسار الحالي. |
| [ClosePath](../../aspose.svg.rendering/idevice/closepath/)() | يغلق المسار الفرعي الحالي بإضافة مقطع خط مستقيم من النقطة الحالية إلى نقطة البداية للمسار الفرعي. إذا كان المسار الفرعي الحالي مغلقًا بالفعل، فإن "ClosePath" لا يفعل شيئًا. هذا المشغل ينهي المسار الفرعي الحالي. إضافة مقطع آخر إلى المسار الحالي يبدأ مسارًا فرعيًا جديدًا، حتى إذا بدأ المقطع الجديد عند نقطة النهاية التي وصل إليها أسلوب "ClosePath". |
| [CubicBezierTo](../../aspose.svg.rendering/idevice/cubicbezierto/)(*PointF, PointF, PointF*) | يضيف منحنى بيزيه تكعيبي إلى المسار الحالي. يمتد المنحنى من النقطة الحالية إلى النقطة pt3، باستخدام pt1 و pt2 كنقاط تحكم بيزيه. النقطة الحالية الجديدة هي pt3. |
| [DrawImage](../../aspose.svg.rendering/idevice/drawimage/)(*byte[], [WebImageFormat](../../aspose.svg.drawing/webimageformat/), RectangleF*) | يرسم الصورة المحددة. |
| [EndDocument](../../aspose.svg.rendering/idevice/enddocument/)() | ينهي تصيير المستند. |
| [EndElement](../../aspose.svg.rendering/idevice/endelement/)(*[Element](../../aspose.svg.dom/element/)*) | ينهي تصيير العنصر. |
| [EndPage](../../aspose.svg.rendering/idevice/endpage/)() | ينهي تصيير الصفحة الحالية. |
| [Fill](../../aspose.svg.rendering/idevice/fill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | يملأ المنطقة الكاملة المحصورة بالمسار الحالي. إذا كان المسار يتكون من عدة مسارات فرعية غير متصلة، فإنه يملأ داخل جميع المسارات الفرعية معًا. تنهي هذه الطريقة المسار الحالي. |
| [FillText](../../aspose.svg.rendering/idevice/filltext/)(*string, PointF*) | يملأ سلسلة النص المحددة في الموقع المحدد. |
| [Flush](../../aspose.svg.rendering/idevice/flush/)() | يفرغ جميع البيانات إلى تدفق الإخراج. |
| [LineTo](../../aspose.svg.rendering/idevice/lineto/)(*PointF*) | يضيف مقطع خط مستقيم من النقطة الحالية إلى النقطة (pt). النقطة الحالية الجديدة هي pt. |
| [MoveTo](../../aspose.svg.rendering/idevice/moveto/)(*PointF*) | يبدأ مسارًا فرعيًا جديدًا بنقل النقطة الحالية إلى إحداثيات المعامل pt، متجنبًا أي مقطع خط يربط بينهما. إذا كانت طريقة إنشاء المسار السابقة في المسار الحالي هي أيضًا "MoveTo"، فإن "MoveTo" الجديد يتجاوزها؛ ولا يبقى أي أثر لعملية "MoveTo" السابقة في المسار. |
| [RestoreGraphicContext](../../aspose.svg.rendering/idevice/restoregraphiccontext/)() | يعيد سياق الرسومات بالكامل إلى قيمته السابقة عن طريق إزالته من المكدس. |
| [SaveGraphicContext](../../aspose.svg.rendering/idevice/savegraphiccontext/)() | يدفع نسخة من سياق الرسومات بالكامل إلى المكدس. |
| [Stroke](../../aspose.svg.rendering/idevice/stroke/)() | يرسم خطًا على طول المسار الحالي. يتبع الخط المرسوم كل مقطع مستقيم أو منحني في المسار، مركّزًا على المقطع مع جوانب موازية له. يتم التعامل مع كل مسار فرعي للمسار بشكل منفصل. تنهي هذه الطريقة المسار الحالي. |
| [StrokeAndFill](../../aspose.svg.rendering/idevice/strokeandfill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | يرسم ويملأ المسار الحالي. تنهي هذه الطريقة المسار الحالي. |
| [StrokeText](../../aspose.svg.rendering/idevice/stroketext/)(*string, PointF*) | يرسم سلسلة النص المحددة في الموقع المحدد. |

### انظر أيضًا

* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
