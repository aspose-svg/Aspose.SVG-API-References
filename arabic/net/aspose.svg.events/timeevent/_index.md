---
title: "فئة TimeEvent"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Events.TimeEvent. توفر واجهة TimeEvent معلومات سياقية محددة **associated** مع أحداث **Time**. الأنواع المختلفة **types** للأحداث التي يمكن حدوثها هي **beginEvent** endEvent و repeatEvent."
type: docs
weight: 3720
url: /ar/net/aspose.svg.events/timeevent/
---
## TimeEvent class

توفر واجهة TimeEvent معلومات سياقية محددة مرتبطة بأحداث الوقت. الأنواع المختلفة للأحداث التي يمكن أن تحدث هي: beginEvent، endEvent و repeatEvent.

```csharp
public class TimeEvent : Event
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | يُستخدم لتحديد ما إذا كان الحدث حدثًا متدفقًا أم لا. إذا كان الحدث يمكن أن يتدفق تكون القيمة true، وإلا تكون القيمة false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | يُستخدم لتحديد ما إذا كان يمكن منع الإجراء الافتراضي للحدث أم لا. إذا كان يمكن منع الإجراء الافتراضي تكون القيمة true، وإلا تكون القيمة false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | يُستخدم للإشارة إلى [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) الذي تُجري حاليًا معالجة [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) الخاصة به. هذا مفيد بشكل خاص أثناء الالتقاط والانتشار. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | يعيد true إذا تم استدعاء preventDefault() بينما تكون قيمة الخاصية cancelable هي true، وإلا يعيد false. |
| [Detail](../../aspose.svg.events/timeevent/detail/) { get; } | يحدد بعض المعلومات التفصيلية حول الحدث، اعتمادًا على النوع **of the event**. لهذا **event type**، يشير إلى رقم التكرار **for the animation**. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | يُستخدم لتحديد أي مرحلة من تدفق الحدث يتم تقييمها حاليًا. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | يجب أن تُعيد الخاصية isTrusted القيمة التي تم تهيئتها بها. عند إنشاء الحدث يجب تهيئة الخاصية إلى false. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | يُستخدم للإشارة إلى [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) الذي تم إرسال الحدث إليه أصلاً. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | يُستخدم لتحديد الوقت (بالمليثانية بالنسبة للحقبة) الذي تم إنشاء الحدث فيه. ونظرًا لأن بعض الأنظمة قد لا توفر هذه المعلومة، قد لا تكون قيمة timeStamp متاحة لجميع الأحداث. عندما لا تكون متاحة، سيتم إرجاع القيمة 0. من أمثلة وقت الحقبة وقت بدء النظام أو 0:0:0 UTC 1 يناير 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | اسم الحدث (غير حساس لحالة الأحرف). يجب أن يكون الاسم اسم XML. |
| [View](../../aspose.svg.events/timeevent/view/) { get; } | تحدد سمة view الـ AbstractView [DOM2VIEWS] التي تم إنشاء الحدث منها. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | يُستخدم الأسلوب [`InitEvent`](../../aspose.svg.dom.events/event/initevent/) لتهيئة قيمة [`Event`](../../aspose.svg.dom.events/event/) تم إنشاؤه عبر واجهة [`IDocumentEvent`](../../aspose.svg.dom.events/idocumentevent/). |
| [InitTimeEvent](../../aspose.svg.events/timeevent/inittimeevent/)(*string, [IAbstractView](../../aspose.svg.dom.views/iabstractview/), long*) | يُستخدم الأسلوب initTimeEvent لتهيئة قيمة TimeEvent تم إنشاؤه عبر واجهة DocumentEvent. لا يمكن استدعاء هذا الأسلوب إلا قبل أن يتم إرسال TimeEvent عبر الأسلوب dispatchEvent، رغم أنه قد يُستدعى عدة مرات خلال تلك المرحلة إذا لزم الأمر. إذا تم استدعاؤه عدة مرات، فإن الاستدعاء النهائي له أولوية. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | إذا كان الحدث قابلًا للإلغاء، يُستخدم الأسلوب [`PreventDefault`](../../aspose.svg.dom.events/event/preventdefault/) للدلالة على أن الحدث سيُلغى، مما يعني أن أي إجراء افتراضي **normally** يتم اتخاذه من قبل التنفيذ كنتيجة **of the event** لن يحدث. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | استدعاء هذا الأسلوب يمنع وصول الحدث إلى أي مستمعي أحداث تم تسجيلهم بعد المستمع الحالي، وعند إرساله في شجرة يمنع أيضًا وصول الحدث إلى أي كائنات أخرى. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | يُستخدم الأسلوب [`StopPropagation`](../../aspose.svg.dom.events/event/stoppropagation/) لمنع المزيد من **propagation** للحدث أثناء تدفق الحدث. |

### انظر أيضًا

* class [Event](../../aspose.svg.dom.events/event/)
* namespace [Aspose.Svg.Events](../../aspose.svg.events/)
* assembly [Aspose.SVG](../../)
