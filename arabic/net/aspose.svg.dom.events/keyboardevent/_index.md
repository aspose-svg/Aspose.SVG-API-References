---
title: "فئة KeyboardEvent"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Dom.Events.KeyboardEvent. توفر واجهة KeyboardEvent معلومات سياقية محددة مرتبطة بأجهزة لوحة المفاتيح. كل حدث لوحة مفاتيح يشير إلى مفتاح باستخدام قيمة. غالبًا ما تُوجه أحداث لوحة المفاتيح إلى العنصر الذي يملك التركيز."
type: docs
weight: 2980
url: /ar/net/aspose.svg.dom.events/keyboardevent/
---
## KeyboardEvent class

واجهة KeyboardEvent تُوفر معلومات سياقية محددة مرتبطة بأجهزة لوحة المفاتيح. كل حدث لوحة مفاتيح يشير إلى مفتاح باستخدام قيمة. عادةً ما تُوجه أحداث لوحة المفاتيح إلى العنصر الذي يملك التركيز.

```csharp
public class KeyboardEvent : UIEvent
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(*string*) | يُنشئ نسخة جديدة من فئة `KeyboardEvent`. |
| [KeyboardEvent](keyboardevent/#constructor_1)(*string, IDictionary&lt;string, object&gt;*) | يُنشئ نسخة جديدة من فئة `KeyboardEvent`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AltKey](../../aspose.svg.dom.events/keyboardevent/altkey/) { get; } | true إذا كان مُعدل المفتاح Alt (البديل) (أو "Option") نشطًا. يجب أن تكون القيمة غير المهيأة لهذه الخاصية false. |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | يُستخدم لتحديد ما إذا كان الحدث حدثًا متدفقًا أم لا. إذا كان الحدث يمكن أن يتدفق تكون القيمة true، وإلا تكون القيمة false. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | يُستخدم لتحديد ما إذا كان يمكن منع الإجراء الافتراضي للحدث أم لا. إذا كان يمكن منع الإجراء الافتراضي تكون القيمة true، وإلا تكون القيمة false. |
| [Code](../../aspose.svg.dom.events/keyboardevent/code/) { get; } | يحمل الكود سلسلة تحدد المفتاح الفعلي المضغوط. لا تتأثر القيمة بتخطيط لوحة المفاتيح الحالي أو حالة المُعدلات، لذا سيُعيد المفتاح المحدد دائمًا نفس القيمة. |
| [CtrlKey](../../aspose.svg.dom.events/keyboardevent/ctrlkey/) { get; } | true إذا كان مُعدل المفتاح Control (التحكم) نشطًا. يجب أن تكون القيمة غير المهيأة لهذه الخاصية false. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | يُستخدم لتحديد الـ[`IEventTarget`](../ieventtarget/) الذي يتم حالياً معالجة الـ[`IEventListener`](../ieventlistener/) الخاص به. هذا مفيد بشكل خاص أثناء الالتقاط والتدفق. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | يعيد true إذا تم استدعاء preventDefault() بينما تكون قيمة الخاصية cancelable هي true، وإلا يعيد false. |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | يحدد بعض المعلومات التفصيلية حول الحدث، حسب نوع الحدث. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | يُستخدم لتحديد أي مرحلة من تدفق الحدث يتم تقييمها حاليًا. |
| [IsComposing](../../aspose.svg.dom.events/keyboardevent/iscomposing/) { get; } | true إذا حدث حدث المفتاح كجزء من جلسة تكوين، أي بعد حدث compositionstart وقبل حدث compositionend المقابل. يجب أن تكون القيمة غير المهيأة لهذه الخاصية false. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | يجب أن تُعيد الخاصية isTrusted القيمة التي تم تهيئتها بها. عند إنشاء الحدث يجب تهيئة الخاصية إلى false. |
| [Key](../../aspose.svg.dom.events/keyboardevent/key/) { get; } | المفتاح يحمل قيمة المفتاح للمفتاح المضغوط. إذا كان للقيمة تمثيل مطبوع، يجب أن تكون سلسلة أحرف يونيكود غير فارغة، متوافقة مع الخوارزمية لتحديد قيمة المفتاح المحددة في هذه المواصفة. إذا كانت القيمة مفتاح تحكم لا يحتوي على تمثيل مطبوع، يجب أن تكون واحدة من قيم المفاتيح المحددة في مجموعة قيم المفاتيح، كما تحددها الخوارزمية لتحديد قيمة المفتاح. يجب على التطبيقات التي لا تستطيع تحديد المفتاح استخدام قيمة المفتاح Unidentified. |
| [Location](../../aspose.svg.dom.events/keyboardevent/location/) { get; } | سمة الموقع تحتوي على إشارة إلى الموقع المنطقي للمفتاح على الجهاز. |
| [MetaKey](../../aspose.svg.dom.events/keyboardevent/metakey/) { get; } | true إذا كان معدل تعديل المفتاح meta (Meta) نشط. |
| [Repeat](../../aspose.svg.dom.events/keyboardevent/repeat/) { get; } | true إذا تم ضغط المفتاح بطريقة مستمرة. يجب أن يؤدي الضغط المستمر على مفتاح إلى تكرار أحداث keydown و beforeinput و input بهذا الترتيب، بمعدل يحدده تكوين النظام. بالنسبة للأجهزة المحمولة التي لديها سلوك ضغط مفتاح طويل، يجب أن يكون أول حدث مفتاح مع قيمة سمة repeat تساوي true إشارة إلى ضغط مفتاح طويل. طول الوقت الذي يجب ضغط المفتاح فيه لبدء التكرار يعتمد على التكوين. |
| [ShiftKey](../../aspose.svg.dom.events/keyboardevent/shiftkey/) { get; } | true إذا كان معدل تعديل المفتاح shift (Shift) نشط. |
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
| const [DOM_KEY_LOCATION_LEFT](../../aspose.svg.dom.events/keyboardevent/dom_key_location_left/) | المفتاح المفعل نشأ من موقع المفتاح الأيسر (عندما يكون هناك أكثر من موقع محتمل لهذا المفتاح). |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.svg.dom.events/keyboardevent/dom_key_location_numpad/) | نشأ تفعيل المفتاح على لوحة الأرقام أو بمفتاح افتراضي يتطابق مع لوحة الأرقام (عندما يكون هناك أكثر من موقع محتمل لهذا المفتاح). لاحظ أن مفتاح NumLock يجب دائمًا أن يُشفّر بموقع DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.svg.dom.events/keyboardevent/dom_key_location_right/) | نشأ تفعيل المفتاح من موقع المفتاح الأيمن (عندما يكون هناك أكثر من موقع محتمل لهذا المفتاح). |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.svg.dom.events/keyboardevent/dom_key_location_standard/) | يجب ألا يتم تمييز تفعيل المفتاح كنسخة يسرى أو يمنى من المفتاح، و(باستثناء مفتاح NumLock) لم ينشأ من لوحة الأرقام (أو لم ينشأ بمفتاح افتراضي يتطابق مع لوحة الأرقام). |

### انظر أيضًا

* class [UIEvent](../uievent/)
* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
