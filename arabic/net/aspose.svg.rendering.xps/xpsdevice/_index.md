---
title: XpsDevice
second_title: Aspose.SVG لمرجع .NET API
description: يمثل التقديم إلى مستند xps .
type: docs
weight: 3000
url: /ar/net/aspose.svg.rendering.xps/xpsdevice/
---
## XpsDevice class

يمثل التقديم إلى مستند xps .

```csharp
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [XpsDevice](xpsdevice#constructor)(ICreateStreamProvider) | يقوم بتهيئة مثيل جديد لملف[`XpsDevice`](../xpsdevice) فئة . |
| [XpsDevice](xpsdevice#constructor_4)(Stream) | يقوم بتهيئة مثيل جديد لملف[`XpsDevice`](../xpsdevice) فئة . |
| [XpsDevice](xpsdevice#constructor_5)(string) | يقوم بتهيئة مثيل جديد لملف[`XpsDevice`](../xpsdevice) فئة . |
| [XpsDevice](xpsdevice#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | يقوم بتهيئة مثيل جديد لملف[`XpsDevice`](../xpsdevice) class عن طريق تقديم الخيارات وموفر البث. |
| [XpsDevice](xpsdevice#constructor_2)(XpsRenderingOptions, Stream) | يقوم بتهيئة مثيل جديد لملف[`XpsDevice`](../xpsdevice) class عن طريق تقديم الخيارات ودفق الإخراج. |
| [XpsDevice](xpsdevice#constructor_3)(XpsRenderingOptions, string) | يقوم بتهيئة مثيل جديد لملف[`XpsDevice`](../xpsdevice) class عن طريق تقديم الخيارات واسم ملف الإخراج. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device`2/graphiccontext) { get; } |  |
| [Options](../../aspose.svg.rendering/device`2/options) { get; } |  |

## طُرق

| اسم | وصف |
| --- | --- |
| override [AddRect](../../aspose.svg.rendering.xps/xpsdevice/addrect)(RectangleF) | إلحاق مستطيل بالمسار الحالي كمسار فرعي كامل. |
| override [BeginDocument](../../aspose.svg.rendering.xps/xpsdevice/begindocument)(Document) | يبدأ عرض المستند. |
| override [BeginElement](../../aspose.svg.rendering.xps/xpsdevice/beginelement)(Element, RectangleF) | يبدأ عرض العنصر. |
| override [BeginPage](../../aspose.svg.rendering.xps/xpsdevice/beginpage)(SizeF) | يبدأ عرض الصفحة الجديدة . |
| override [Clip](../../aspose.svg.rendering.xps/xpsdevice/clip)(FillMode) | يعدل مسار القطع الحالي عن طريق تقاطعه مع المسار الحالي ، باستخدام قاعدة FillMode لتحديد المنطقة المراد تعبئتها. تنهي هذه الطريقة المسار الحالي. |
| override [ClosePath](../../aspose.svg.rendering.xps/xpsdevice/closepath)() | لإغلاق المسار الفرعي الحالي بإلحاق مقطع بخط مستقيم من النقطة الحالية إلى نقطة بداية المسار الفرعي. إذا كان المسار الفرعي الحالي مغلقًا بالفعل ، فإن "ClosePath" لا يفعل شيئًا . ينهي عامل التشغيل هذا المسار الفرعي الحالي. يؤدي إلحاق مقطع آخر بالمسار الحالي إلى بدء مسار فرعي جديد ، حتى إذا بدأ المقطع الجديد عند نقطة النهاية التي تم الوصول إليها بواسطة طريقة "ClosePath" . |
| override [CubicBezierTo](../../aspose.svg.rendering.xps/xpsdevice/cubicbezierto)(PointF, PointF, PointF) | لإلحاق منحنى بيزير مكعب بالمسار الحالي. يمتد المنحنى من النقطة الحالية إلى النقطة pt2 ، باستخدام pt1 و pt2 كنقاط تحكم Bézier. النقطة الحالية الجديدة هي pt3. |
| [Dispose](../../aspose.svg.rendering/device`2/dispose)() |  |
| override [DrawImage](../../aspose.svg.rendering.xps/xpsdevice/drawimage)(byte[], ImageType, RectangleF) | يرسم الصورة المحددة . |
| virtual [EndDocument](../../aspose.svg.rendering/device`2/enddocument)() |  |
| override [EndElement](../../aspose.svg.rendering.xps/xpsdevice/endelement)(Element) | ينتهي عرض العنصر. |
| override [EndPage](../../aspose.svg.rendering.xps/xpsdevice/endpage)() | ينتهي عرض الصفحة الحالية. |
| override [Fill](../../aspose.svg.rendering.xps/xpsdevice/fill)(FillMode) | يملأ المنطقة بأكملها المحاطة بالمسار الحالي. إذا كان المسار يتكون من عدة مسارات فرعية غير متصلة ، فإنه يملأ الدواخل لجميع المسارات الفرعية ، تعتبر معًا. تنهي هذه الطريقة المسار الحالي. |
| override [FillText](../../aspose.svg.rendering.xps/xpsdevice/filltext)(string, PointF) | يملأ السلسلة النصية المحددة في المكان المحدد. |
| override [Flush](../../aspose.svg.rendering.xps/xpsdevice/flush)() | مسح جميع البيانات لإخراج التدفق. |
| override [LineTo](../../aspose.svg.rendering.xps/xpsdevice/lineto)(PointF) | لإلحاق مقطع خط مستقيم من النقطة الحالية بالنقطة (نقطة). النقطة الحالية الجديدة هي pt. |
| override [MoveTo](../../aspose.svg.rendering.xps/xpsdevice/moveto)(PointF) | يبدأ مسارًا فرعيًا جديدًا عن طريق تحريك النقطة الحالية إلى إحداثيات المعلمة pt ، مع حذف أي مقطع خط متصل. إذا كانت طريقة إنشاء المسار السابقة في المسار الحالي هي أيضًا "MoveTo" ، فإن "MoveTo" الجديد يتجاوزها ؛ لا توجد آثار لعملية "MoveTo" السابقة في المسار. |
| override [RestoreGraphicContext](../../aspose.svg.rendering.xps/xpsdevice/restoregraphiccontext)() | يعيد سياق الرسومات بالكامل إلى قيمته السابقة عن طريق إخراجه من المكدس. |
| virtual [SaveGraphicContext](../../aspose.svg.rendering/device`2/savegraphiccontext)() |  |
| override [Stroke](../../aspose.svg.rendering.xps/xpsdevice/stroke)() | رسم خط بطول المسار الحالي. يتبع الخط المحدد كل مقطع مستقيم أو منحني في المسار ، متمركزًا على المقطع مع جوانب موازية له. يتم التعامل مع كل من المسارات الفرعية للمسار بشكل منفصل. تنهي هذه الطريقة المسار الحالي. |
| override [StrokeAndFill](../../aspose.svg.rendering.xps/xpsdevice/strokeandfill)(FillMode) | ضربات وملء المسار الحالي. تنهي هذه الطريقة المسار الحالي. |
| override [StrokeText](../../aspose.svg.rendering.xps/xpsdevice/stroketext)(string, PointF) | ضربات السلسلة النصية المحددة في الموقع المحدد. |

## أعضاء آخرون

| اسم | وصف |
| --- | --- |
| class [XpsGraphicContext](xpsdevice.xpsgraphiccontext) | يحمل معلمات التحكم في الرسومات الحالية لجهاز XpsDevice. تحدد هذه المعلمات الإطار العام الذي ينفذ فيه مشغلو الرسومات. |

### أنظر أيضا

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.svg.rendering/device-2)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext)
* class [XpsRenderingOptions](../xpsrenderingoptions)
* مساحة الاسم [Aspose.Svg.Rendering.Xps](../../aspose.svg.rendering.xps)
* المجسم [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
