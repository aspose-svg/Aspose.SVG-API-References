---
title: "فئة DeviceTGraphicContextTRenderingOptions"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Rendering.Device2TGraphicContextTRenderingOptions class. يمثل الفئة الأساسية لتنفيذ أجهزة التصيير الخاصة."
type: docs
weight: 4820
url: /ar/net/aspose.svg.rendering/device-2/
---
## Device<TGraphicContext,TRenderingOptions> class

يمثل الفئة الأساسية لتنفيذ أجهزة العرض المحددة.

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| معامل | الوصف |
| --- | --- |
| TGraphicContext | سياق رسومي يحتفظ بمعلمات التحكم الرسومية الحالية |
| TRenderingOptions | خيارات التصيير |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } | يحصل على سياق الرسومات |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } | يحصل على خيارات التصيير. |
| virtual [Configuration](../../aspose.svg.rendering/device-2/configuration/) { get; } | يحصل على تكوين الجهاز. |
| [OutputStream](../../aspose.svg.rendering/device-2/outputstream/) { get; } | يضبط ويسترجع تدفق الإخراج. |
| [StreamProvider](../../aspose.svg.rendering/device-2/streamprovider/) { get; } | يحصل على كائن موفر التدفق. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [AddRect](../../aspose.svg.rendering/device-2/addrect/)(*RectangleF*) | يضيف مستطيلًا إلى المسار الحالي كمسار فرعي كامل. |
| virtual [BeginDocument](../../aspose.svg.rendering/device-2/begindocument/)(*[Document](../../aspose.svg.dom/document/)*) | يبدأ تصيير المستند. |
| virtual [BeginElement](../../aspose.svg.rendering/device-2/beginelement/)(*[Element](../../aspose.svg.dom/element/), RectangleF*) | يبدأ رسم العقدة. |
| virtual [BeginPage](../../aspose.svg.rendering/device-2/beginpage/)(*SizeF*) | يبدأ تصيير الصفحة الجديدة. |
| virtual [Clip](../../aspose.svg.rendering/device-2/clip/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | يعدّل مسار القص الحالي عن طريق تقاطعه مع المسار الحالي، باستخدام FillRule لتحديد المنطقة التي يجب ملؤها. تنهي هذه الطريقة المسار الحالي. |
| virtual [ClosePath](../../aspose.svg.rendering/device-2/closepath/)() | يغلق المسار الفرعي الحالي بإضافة مقطع خط مستقيم من النقطة الحالية إلى نقطة البداية للمسار الفرعي. إذا كان المسار الفرعي الحالي مغلقًا بالفعل، فإن "ClosePath" لا يفعل شيئًا. هذا المشغل ينهي المسار الفرعي الحالي. إضافة مقطع آخر إلى المسار الحالي يبدأ مسارًا فرعيًا جديدًا، حتى إذا بدأ المقطع الجديد عند نقطة النهاية التي وصل إليها أسلوب "ClosePath". |
| virtual [CubicBezierTo](../../aspose.svg.rendering/device-2/cubicbezierto/)(*PointF, PointF, PointF*) | يضيف منحنى بيزيه مكعب إلى المسار الحالي. يمتد المنحنى من النقطة الحالية إلى النقطة pt2، باستخدام pt1 و pt2 كنقاط تحكم بيزيه. النقطة الحالية الجديدة هي pt3. |
| [Dispose](../../aspose.svg.rendering/device-2/dispose/)() | ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة تعيين الموارد غير المُدارة. |
| virtual [DrawImage](../../aspose.svg.rendering/device-2/drawimage/)(*byte[], [WebImageFormat](../../aspose.svg.drawing/webimageformat/), RectangleF*) | يرسم الصورة المحددة. |
| virtual [EndDocument](../../aspose.svg.rendering/device-2/enddocument/)() | ينهي تصيير المستند. |
| virtual [EndElement](../../aspose.svg.rendering/device-2/endelement/)(*[Element](../../aspose.svg.dom/element/)*) | ينهي رسم العقدة. |
| virtual [EndPage](../../aspose.svg.rendering/device-2/endpage/)() | ينهي تصيير الصفحة الحالية. |
| virtual [Fill](../../aspose.svg.rendering/device-2/fill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | يملأ المنطقة الكاملة المحصورة بالمسار الحالي. إذا كان المسار يتكون من عدة مسارات فرعية غير متصلة، فإنه يملأ داخل جميع المسارات الفرعية معًا. تنهي هذه الطريقة المسار الحالي. |
| virtual [FillText](../../aspose.svg.rendering/device-2/filltext/)(*string, PointF*) | يملأ سلسلة النص المحددة في الموقع المحدد. |
| virtual [Flush](../../aspose.svg.rendering/device-2/flush/)() | يفرغ جميع البيانات إلى تدفق الإخراج. |
| virtual [LineTo](../../aspose.svg.rendering/device-2/lineto/)(*PointF*) | يضيف مقطع خط مستقيم من النقطة الحالية إلى النقطة (pt). النقطة الحالية الجديدة هي pt. |
| virtual [MoveTo](../../aspose.svg.rendering/device-2/moveto/)(*PointF*) | يبدأ مسارًا فرعيًا جديدًا بنقل النقطة الحالية إلى إحداثيات المعامل pt، متجنبًا أي مقطع خط يربط بينهما. إذا كانت طريقة إنشاء المسار السابقة في المسار الحالي هي أيضًا "MoveTo"، فإن "MoveTo" الجديد يتجاوزها؛ ولا يبقى أي أثر لعملية "MoveTo" السابقة في المسار. |
| virtual [RestoreGraphicContext](../../aspose.svg.rendering/device-2/restoregraphiccontext/)() | يعيد سياق الرسومات بالكامل إلى قيمته السابقة عن طريق إزالته من المكدس. |
| virtual [SaveGraphicContext](../../aspose.svg.rendering/device-2/savegraphiccontext/)() | يدفع نسخة من سياق الرسومات بالكامل إلى المكدس. |
| virtual [Stroke](../../aspose.svg.rendering/device-2/stroke/)() | يرسم خطًا على طول المسار الحالي. يتبع الخط المرسوم كل مقطع مستقيم أو منحني في المسار، مركّزًا على المقطع مع جوانب موازية له. يتم التعامل مع كل مسار فرعي للمسار بشكل منفصل. تنهي هذه الطريقة المسار الحالي. |
| virtual [StrokeAndFill](../../aspose.svg.rendering/device-2/strokeandfill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | يرسم ويملأ المسار الحالي. تنهي هذه الطريقة المسار الحالي. |
| virtual [StrokeText](../../aspose.svg.rendering/device-2/stroketext/)(*string, PointF*) | يرسم سلسلة النص المحددة في الموقع المحدد. |

## الأعضاء الأخرى

| الاسم | الوصف |
| --- | --- |
| class [DeviceConfiguration<TGraphicContext,TRenderingOptions>](../../aspose.svg.rendering/device-2.deviceconfiguration-2) | تمثل كائن تكوين للأجهزة. |
| enum [PageWritingStrategy<TGraphicContext,TRenderingOptions>](../../aspose.svg.rendering/device-2.pagewritingstrategy-2) | يحدد أنواع الاستراتيجيات لكتابة الصفحات إلى تدفق\تدفقات الإخراج. |

### انظر أيضًا

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
