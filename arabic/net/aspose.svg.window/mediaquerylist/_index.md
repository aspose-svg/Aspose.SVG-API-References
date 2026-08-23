---
title: "فئة MediaQueryList"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Window.MediaQueryList. يخزن كائن MediaQueryList معلومات حول استعلام وسائط (media query) يُطبق على مستند مع دعم لكل من المطابقة الفورية والمستندة إلى الأحداث ضد حالة المستند. راجع مواصفة CSSOM View Module على https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs
weight: 5960
url: /ar/net/aspose.svg.window/mediaquerylist/
---
## MediaQueryList class

يخزن كائن MediaQueryList معلومات حول استعلام وسائط مطبق على مستند، مع دعم للمطابقة الفورية والمستندة إلى الأحداث ضد حالة المستند. راجع مواصفة وحدة عرض CSSOM: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```csharp
public class MediaQueryList : EventTarget
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Document](../../aspose.svg.window/mediaquerylist/document/) { get; } | المستند المرتبط بكائن السياق. |
| [Matches](../../aspose.svg.window/mediaquerylist/matches/) { get; } | قيمة منطقية تُعيد true إذا كان المستند يطابق حاليًا قائمة استعلامات الوسائط، أو false إذا لم يحدث ذلك. |
| [Media](../../aspose.svg.window/mediaquerylist/media/) { get; } | سلسلة نصية تمثل استعلام وسائط مسلسل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | يضبط دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | يضبط دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | يضبط دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [AddListener](../../aspose.svg.window/mediaquerylist/addlistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | إضافة مستمع حدث لتغيير حالة المطابقة في MediaQueryList. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | يبثّ حدثًا إلى [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/)، (متزامنًا) مستدعيًا مستمعي الأحداث المتأثرين بالترتيب المناسب. تُطبق قواعد معالجة الأحداث العادية (بما في ذلك مرحلة الالتقاط والفقاعة الاختيارية) أيضًا على الأحداث التي تُبث يدويًا باستخدام [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة تعيين الموارد غير المُدارة. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | تتيح هذه الطريقة إزالة مستمعي الأحداث من هدف الحدث. إذا تمت إزالة [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) من [`EventTarget`](../../aspose.svg.dom/eventtarget/) أثناء معالجته لحدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتهم. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | تتيح هذه الطريقة إزالة مستمعي الأحداث من هدف الحدث. إذا تمت إزالة [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) من [`EventTarget`](../../aspose.svg.dom/eventtarget/) أثناء معالجته لحدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتهم. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | تتيح هذه الطريقة إزالة مستمعي الأحداث من هدف الحدث. إذا تمت إزالة [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) من [`EventTarget`](../../aspose.svg.dom/eventtarget/) أثناء معالجته لحدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتهم. |
| [RemoveListener](../../aspose.svg.window/mediaquerylist/removelistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | إزالة مستمع حدث لتغيير حالة المطابقة في MediaQueryList. |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [OnChange](../../aspose.svg.window/mediaquerylist/onchange/) | الحدث الذي يُطلق على MediaQueryList عندما تتغير حالة المطابقة. |

### انظر أيضًا

* class [EventTarget](../../aspose.svg.dom/eventtarget/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
