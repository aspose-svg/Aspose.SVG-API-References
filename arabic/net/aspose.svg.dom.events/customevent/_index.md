---
title: "فئة CustomEvent"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Dom.Events.CustomEvent. يمكن استخدام الأحداث التي تستعمل واجهة CustomEvent لحمل بيانات مخصصة"
type: docs
weight: 2880
url: /ar/net/aspose.svg.dom.events/customevent/
---
## CustomEvent class

يمكن استخدام الأحداث عبر واجهة CustomEvent لنقل بيانات مخصصة.

```csharp
public class CustomEvent : Event
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [CustomEvent](customevent/#constructor)(*string*) | يُنشئ مثيلاً جديدًا من الفئة `CustomEvent`. |
| [CustomEvent](customevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | يُنشئ مثيلاً جديدًا من الفئة `CustomEvent`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | يُستخدم لتحديد ما إذا كان الحدث حدثًا متدفقًا أم لا. إذا كان الحدث يمكن أن يتدفق تكون القيمة true، وإلا تكون القيمة false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | يُستخدم لتحديد ما إذا كان يمكن منع الإجراء الافتراضي للحدث أم لا. إذا كان يمكن منع الإجراء الافتراضي تكون القيمة true، وإلا تكون القيمة false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | يُستخدم لتحديد الـ[`IEventTarget`](../ieventtarget/) الذي يتم حالياً معالجة الـ[`IEventListener`](../ieventlistener/) الخاص به. هذا مفيد بشكل خاص أثناء الالتقاط والتدفق. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | يعيد true إذا تم استدعاء preventDefault() بينما تكون قيمة الخاصية cancelable هي true، وإلا يعيد false. |
| [Detail](../../aspose.svg.dom.events/customevent/detail/) { get; } | يحصل على البيانات المخصصة. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | يُستخدم لتحديد أي مرحلة من تدفق الحدث يتم تقييمها حاليًا. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | يجب أن تُعيد الخاصية isTrusted القيمة التي تم تهيئتها بها. عند إنشاء الحدث يجب تهيئة الخاصية إلى false. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | يُستخدم لتحديد الـ[`IEventTarget`](../ieventtarget/) الذي تم إرسال الحدث إليه أصلاً. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | يُستخدم لتحديد الوقت (بالمليثانية بالنسبة للحقبة) الذي تم إنشاء الحدث فيه. ونظرًا لأن بعض الأنظمة قد لا توفر هذه المعلومة، قد لا تكون قيمة timeStamp متاحة لجميع الأحداث. عندما لا تكون متاحة، سيتم إرجاع القيمة 0. من أمثلة وقت الحقبة وقت بدء النظام أو 0:0:0 UTC 1 يناير 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | اسم الحدث (غير حساس لحالة الأحرف). يجب أن يكون الاسم اسم XML. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [InitCustomEvent](../../aspose.svg.dom.events/customevent/initcustomevent/)(*string, bool, bool, object*) | /// تُستخدم طريقة [`InitEvent`](../event/initevent/) لتهيئة قيمة [`Event`](../event/) التي تم إنشاؤها عبر واجهة [`IDocumentEvent`](../idocumentevent/). |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | يُستخدم الأسلوب [`InitEvent`](../event/initevent/) لتهيئة قيمة الـ[`Event`](../event/) الذي تم إنشاؤه عبر واجهة [`IDocumentEvent`](../idocumentevent/). |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | إذا كان الحدث قابلًا للإلغاء، يُستخدم الأسلوب [`PreventDefault`](../event/preventdefault/) للدلالة على أن الحدث يجب إلغاؤه، مما يعني أن أي إجراء افتراضي عادةً ما تتخذّه التنفيذ نتيجةً للحدث لن يحدث. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | استدعاء هذا الأسلوب يمنع وصول الحدث إلى أي مستمعي أحداث تم تسجيلهم بعد المستمع الحالي، وعند إرساله في شجرة يمنع أيضًا وصول الحدث إلى أي كائنات أخرى. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | يُستخدم الأسلوب [`StopPropagation`](../event/stoppropagation/) لمنع انتشار إضافي للحدث أثناء تدفق الحدث. |

### انظر أيضًا

* class [Event](../event/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
