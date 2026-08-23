---
title: "واجهة IEventTarget"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "واجهة Aspose.Svg.Dom.Events.IEventTarget. يتم تنفيذ واجهة EventTarget بواسطة جميع العقد (Nodes) في تنفيذ يدعم نموذج أحداث DOM. لذلك يمكن الحصول على هذه الواجهة باستخدام أساليب التحويل الخاصة بالربط على مثيل من واجهة Node. تسمح الواجهة بتسجيل وإزالة مستمعي الأحداث على EventTarget وإرسال الأحداث إلى ذلك IEventTarget."
type: docs
weight: 2960
url: /ar/net/aspose.svg.dom.events/ieventtarget/
---
## IEventTarget interface

The interface [`EventTarget`](../../aspose.svg.dom/eventtarget/) يتم تنفيذها من قبل جميع العقد في تنفيذ يدعم نموذج أحداث DOM. لذلك، يمكن الحصول على هذه الواجهة باستخدام طرق التحويل الخاصة بالربط على كائن من واجهة العقدة. تسمح الواجهة بالتسجيل وإزالة مستمعي الأحداث على [`EventTarget`](../../aspose.svg.dom/eventtarget/) وإرسال الأحداث إلى ذلك `IEventTarget`.

```csharp
public interface IEventTarget
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom.events/ieventtarget/addeventlistener/#addeventlistener)(*string, [IEventListener](../ieventlistener/)*) | تسمح هذه الطريقة بتسجيل مستمعي الأحداث على هدف الحدث. |
| [AddEventListener](../../aspose.svg.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | تسمح هذه الطريقة بتسجيل مستمعي الأحداث على هدف الحدث. |
| [DispatchEvent](../../aspose.svg.dom.events/ieventtarget/dispatchevent/)(*[Event](../event/)*) | تسمح هذه الطريقة بإرسال الأحداث إلى نموذج الأحداث الخاص بالتنفيذ. |
| [RemoveEventListener](../../aspose.svg.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(*string, [IEventListener](../ieventlistener/)*) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة [`IEventListener`](../ieventlistener/) من [`EventTarget`](../../aspose.svg.dom/eventtarget/) أثناء معالجة حدث، فلن يتم تشغيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتهم. |
| [RemoveEventListener](../../aspose.svg.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(*string, [IEventListener](../ieventlistener/), bool*) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة [`IEventListener`](../ieventlistener/) من [`EventTarget`](../../aspose.svg.dom/eventtarget/) أثناء معالجة حدث، فلن يتم تشغيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتهم. |

### انظر أيضًا

* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
