---
title: "فئة WheelEvent"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Dom.Events.WheelEvent. توفر واجهة WheelEvent معلومات سياقية محددة مرتبطة بأحداث العجلة. لإنشاء مثيل من واجهة WheelEvent استخدم مُنشئ WheelEvent مع تمرير قاموس WheelEventInit اختياري"
type: docs
weight: 3010
url: /ar/net/aspose.svg.dom.events/wheelevent/
---
## WheelEvent class

واجهة WheelEvent تُوفر معلومات سياقية محددة مرتبطة بأحداث العجلة. لإنشاء مثال من واجهة WheelEvent، استخدم مُنشئ WheelEvent، مع تمرير قاموس WheelEventInit اختياري.

```csharp
public class WheelEvent : MouseEvent
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(*string*) | يُنشئ مثيلًا جديدًا من فئة `WheelEvent`. |
| [WheelEvent](wheelevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | يُنشئ مثيلًا جديدًا من فئة `WheelEvent`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AltKey](../../aspose.svg.dom.events/mouseevent/altkey/) { get; } | ارجع إلى السمة altKey. |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | يُستخدم لتحديد ما إذا كان الحدث حدثًا متدفقًا أم لا. إذا كان الحدث يمكن أن يتدفق تكون القيمة true، وإلا تكون القيمة false. |
| [Button](../../aspose.svg.dom.events/mouseevent/button/) { get; } | أثناء أحداث الفأرة الناجمة عن ضغط أو تحرير زر الفأرة، يجب استخدام button للإشارة إلى أي زر من جهاز الإشارة تغير حالته. |
| [Buttons](../../aspose.svg.dom.events/mouseevent/buttons/) { get; } | أثناء أي أحداث للفأرة، يجب استخدام buttons للإشارة إلى أي تركيبة من أزرار الفأرة يتم ضغطها حالياً، معبرًا عنها كقناع بتات. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | يُستخدم لتحديد ما إذا كان يمكن منع الإجراء الافتراضي للحدث أم لا. إذا كان يمكن منع الإجراء الافتراضي تكون القيمة true، وإلا تكون القيمة false. |
| [ClientX](../../aspose.svg.dom.events/mouseevent/clientx/) { get; } | الإحداثي الأفقي الذي وقع فيه الحدث بالنسبة لمنطقة العرض المرتبطة بالحدث. |
| [ClientY](../../aspose.svg.dom.events/mouseevent/clienty/) { get; } | الإحداثي الرأسي الذي وقع فيه الحدث بالنسبة لمنطقة العرض المرتبطة بالحدث. |
| [CtrlKey](../../aspose.svg.dom.events/mouseevent/ctrlkey/) { get; } | ارجع إلى السمة ctrlKey. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | يُستخدم لتحديد الـ[`IEventTarget`](../ieventtarget/) الذي يتم حالياً معالجة الـ[`IEventListener`](../ieventlistener/) الخاص به. هذا مفيد بشكل خاص أثناء الالتقاط والتدفق. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | يعيد true إذا تم استدعاء preventDefault() بينما تكون قيمة الخاصية cancelable هي true، وإلا يعيد false. |
| [DeltaMode](../../aspose.svg.dom.events/wheelevent/deltamode/) { get; } | تحتوي خاصية deltaMode على إشارة إلى وحدات القياس لقيم الدلتا. القيمة الافتراضية هي DOM_DELTA_PIXEL (بكسل). |
| [DeltaX](../../aspose.svg.dom.events/wheelevent/deltax/) { get; } | في المتصفحات التي يكون الإجراء الافتراضي لحدث العجلة هو التمرير، يجب أن تكون القيمة هي القياس على المحور x (بالبكسل أو السطور أو الصفحات) التي سيتم تمريرها في حالة عدم إلغاء الحدث. وإلا، فإن هذا قياس خاص بالتنفيذ (بالبكسل أو السطور أو الصفحات) لحركة جهاز العجلة حول المحور x. |
| [DeltaY](../../aspose.svg.dom.events/wheelevent/deltay/) { get; } | في المتصفحات التي يكون الإجراء الافتراضي لحدث العجلة هو التمرير، يجب أن تكون القيمة هي القياس على المحور y (بالبكسل أو السطور أو الصفحات) التي سيتم تمريرها في حالة عدم إلغاء الحدث. وإلا، فإن هذا قياس خاص بالتنفيذ (بالبكسل أو السطور أو الصفحات) لحركة جهاز العجلة حول المحور y. |
| [DeltaZ](../../aspose.svg.dom.events/wheelevent/deltaz/) { get; } | في المتصفحات التي يكون الإجراء الافتراضي لحدث العجلة هو التمرير، يجب أن تكون القيمة هي القياس على المحور z (بالبكسل أو السطور أو الصفحات) التي سيتم تمريرها في حالة عدم إلغاء الحدث. وإلا، فإن هذا قياس خاص بالتنفيذ (بالبكسل أو السطور أو الصفحات) لحركة جهاز العجلة حول المحور z. |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | يحدد بعض المعلومات التفصيلية حول الحدث، حسب نوع الحدث. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | يُستخدم لتحديد أي مرحلة من تدفق الحدث يتم تقييمها حاليًا. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | يجب أن تُعيد الخاصية isTrusted القيمة التي تم تهيئتها بها. عند إنشاء الحدث يجب تهيئة الخاصية إلى false. |
| [MetaKey](../../aspose.svg.dom.events/mouseevent/metakey/) { get; } | ارجع إلى السمة metaKey. |
| [RelatedTarget](../../aspose.svg.dom.events/mouseevent/relatedtarget/) { get; } | يُستخدم لتحديد EventTarget ثانوي مرتبط بحدث واجهة المستخدم، اعتمادًا على نوع الحدث. |
| [ScreenX](../../aspose.svg.dom.events/mouseevent/screenx/) { get; } | الإحداثي الأفقي الذي وقع فيه الحدث بالنسبة لأصل نظام إحداثيات الشاشة. |
| [ScreenY](../../aspose.svg.dom.events/mouseevent/screeny/) { get; } | الإحداثي الرأسي الذي وقع فيه الحدث بالنسبة لأصل نظام إحداثيات الشاشة. |
| [ShiftKey](../../aspose.svg.dom.events/mouseevent/shiftkey/) { get; } | ارجع إلى السمة shiftKey. |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | يُستخدم لتحديد الـ[`IEventTarget`](../ieventtarget/) الذي تم إرسال الحدث إليه أصلاً. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | يُستخدم لتحديد الوقت (بالمليثانية بالنسبة للحقبة) الذي تم إنشاء الحدث فيه. ونظرًا لأن بعض الأنظمة قد لا توفر هذه المعلومة، قد لا تكون قيمة timeStamp متاحة لجميع الأحداث. عندما لا تكون متاحة، سيتم إرجاع القيمة 0. من أمثلة وقت الحقبة وقت بدء النظام أو 0:0:0 UTC 1 يناير 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | اسم الحدث (غير حساس لحالة الأحرف). يجب أن يكون الاسم اسم XML. |
| [View](../../aspose.svg.dom.events/uievent/view/) { get; } | سمة view تحدد النافذة التي تم توليد الحدث منها. يجب أن تكون القيمة غير المبدئية لهذه السمة null. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(*string, bool, bool*) | يُستخدم الأسلوب [`InitEvent`](../event/initevent/) لتهيئة قيمة الـ[`Event`](../event/) الذي تم إنشاؤه عبر واجهة [`IDocumentEvent`](../idocumentevent/). |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | إذا كان الحدث قابلًا للإلغاء، يُستخدم الأسلوب [`PreventDefault`](../event/preventdefault/) للدلالة على أن الحدث يجب إلغاؤه، مما يعني أن أي إجراء افتراضي عادةً ما تتخذّه التنفيذ نتيجةً للحدث لن يحدث. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | استدعاء هذا الأسلوب يمنع وصول الحدث إلى أي مستمعي أحداث تم تسجيلهم بعد المستمع الحالي، وعند إرساله في شجرة يمنع أيضًا وصول الحدث إلى أي كائنات أخرى. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | يُستخدم الأسلوب [`StopPropagation`](../event/stoppropagation/) لمنع انتشار إضافي للحدث أثناء تدفق الحدث. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [DOM_DELTA_LINE](../../aspose.svg.dom.events/wheelevent/dom_delta_line/) | يجب أن تكون وحدات قياس الدلتا هي سطور نصية فردية. هذا هو الحال للعديد من عناصر التحكم في النماذج. |
| const [DOM_DELTA_PAGE](../../aspose.svg.dom.events/wheelevent/dom_delta_page/) | يجب أن تكون وحدات قياس الدلتا هي صفحات، إما معرفة كشاشة واحدة أو كصفحة محددة. |
| const [DOM_DELTA_PIXEL](../../aspose.svg.dom.events/wheelevent/dom_delta_pixel/) | يجب أن تكون وحدات قياس الدلتا هي بكسل. هذا هو الحالة الأكثر شيوعًا في معظم أنظمة التشغيل وتكوينات التنفيذ. |

### انظر أيضًا

* class [MouseEvent](../mouseevent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
