---
title: "فئة SVGZoomEvent"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Events.SVGZoomEvent. يحدث حدث التكبير عندما يبدأ المستخدم إجراءً يؤدي إلى إعادة تحجيم العرض الحالي لمجزوء مستند SVG. يتم التعرف على معالجات الأحداث فقط على عناصر svg."
type: docs
weight: 3710
url: /ar/net/aspose.svg.events/svgzoomevent/
---
## SVGZoomEvent class

يحدث حدث التكبير عندما يبدأ المستخدم إجراءً يؤدي إلى إعادة تحجيم العرض الحالي لجزء وثيقة SVG. يتم التعرف على معالجات الأحداث فقط على عناصر ‘svg’.

```csharp
public class SVGZoomEvent : Event
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | يُستخدم لتحديد ما إذا كان الحدث حدثًا متدفقًا أم لا. إذا كان الحدث يمكن أن يتدفق تكون القيمة true، وإلا تكون القيمة false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | يُستخدم لتحديد ما إذا كان يمكن منع الإجراء الافتراضي للحدث أم لا. إذا كان يمكن منع الإجراء الافتراضي تكون القيمة true، وإلا تكون القيمة false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | يُستخدم للإشارة إلى [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) الذي تُجري حاليًا معالجة [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) الخاصة به. هذا مفيد بشكل خاص أثناء الالتقاط والانتشار. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | يعيد true إذا تم استدعاء preventDefault() بينما تكون قيمة الخاصية cancelable هي true، وإلا يعيد false. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | يُستخدم لتحديد أي مرحلة من تدفق الحدث يتم تقييمها حاليًا. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | يجب أن تُعيد الخاصية isTrusted القيمة التي تم تهيئتها بها. عند إنشاء الحدث يجب تهيئة الخاصية إلى false. |
| [NewScale](../../aspose.svg.events/svgzoomevent/newscale/) { get; } | عامل المقياس الذي سيكون ساريًا بعد معالجة عملية التكبير. |
| [NewTranslate](../../aspose.svg.events/svgzoomevent/newtranslate/) { get; } | قِيَم الترجمة التي ستكون سارية بعد معالجة عملية التكبير. كائن SVGPoint للقراءة فقط. |
| [PreviousScale](../../aspose.svg.events/svgzoomevent/previousscale/) { get; } | عامل المقياس من عمليات التكبير السابقة الذي كان ساريًا قبل حدوث عملية التكبير. |
| [PreviousTranslate](../../aspose.svg.events/svgzoomevent/previoustranslate/) { get; } | قِيَم الترجمة من عمليات التكبير السابقة التي كانت سارية قبل حدوث عملية التكبير. كائن SVGPoint للقراءة فقط. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | يُستخدم للإشارة إلى [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) الذي تم إرسال الحدث إليه أصلاً. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | يُستخدم لتحديد الوقت (بالمليثانية بالنسبة للحقبة) الذي تم إنشاء الحدث فيه. ونظرًا لأن بعض الأنظمة قد لا توفر هذه المعلومة، قد لا تكون قيمة timeStamp متاحة لجميع الأحداث. عندما لا تكون متاحة، سيتم إرجاع القيمة 0. من أمثلة وقت الحقبة وقت بدء النظام أو 0:0:0 UTC 1 يناير 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | اسم الحدث (غير حساس لحالة الأحرف). يجب أن يكون الاسم اسم XML. |
| [ZoomRectScreen](../../aspose.svg.events/svgzoomevent/zoomrectscreen/) { get; } | المستطيل المحدد للتكبير بوحدات الشاشة. كائن SVGRect للقراءة فقط. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | يُستخدم الأسلوب [`InitEvent`](../../aspose.svg.dom.events/event/initevent/) لتهيئة قيمة [`Event`](../../aspose.svg.dom.events/event/) تم إنشاؤه عبر واجهة [`IDocumentEvent`](../../aspose.svg.dom.events/idocumentevent/). |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | إذا كان الحدث قابلًا للإلغاء، يُستخدم الأسلوب [`PreventDefault`](../../aspose.svg.dom.events/event/preventdefault/) للدلالة على أن الحدث سيُلغى، مما يعني أن أي إجراء افتراضي **normally** يتم اتخاذه من قبل التنفيذ كنتيجة **of the event** لن يحدث. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | استدعاء هذا الأسلوب يمنع وصول الحدث إلى أي مستمعي أحداث تم تسجيلهم بعد المستمع الحالي، وعند إرساله في شجرة يمنع أيضًا وصول الحدث إلى أي كائنات أخرى. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | يُستخدم الأسلوب [`StopPropagation`](../../aspose.svg.dom.events/event/stoppropagation/) لمنع المزيد من **propagation** للحدث أثناء تدفق الحدث. |

### انظر أيضًا

* class [Event](../../aspose.svg.dom.events/event/)
* namespace [Aspose.Svg.Events](../../aspose.svg.events/)
* assembly [Aspose.SVG](../../)
