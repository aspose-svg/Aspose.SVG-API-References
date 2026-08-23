---
title: "IEventListener واجهة"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Dom.Events.IEventListener واجهة. واجهة IEventListener هي الطريقة الأساسية لمعالجة الأحداث. يقوم المستخدمون بتنفيذ واجهة IEventListener وتسجيل المستمع الخاص بهم على EventTarget باستخدام طريقة AddEventListener. يجب على المستخدمين أيضًا إزالة IEventListener من EventTarget الخاص به بعد الانتهاء من استخدام المستمع."
type: docs
weight: 2950
url: /ar/net/aspose.svg.dom.events/ieventlistener/
---
## IEventListener interface

واجهة `IEventListener` هي الطريقة الأساسية لمعالجة الأحداث. يقوم المستخدمون بتنفيذ واجهة `IEventListener` وتسجيل المستمع الخاص بهم على [`EventTarget`](../../aspose.svg.dom/eventtarget/) باستخدام طريقة [`AddEventListener`](../../aspose.svg.dom/eventtarget/addeventlistener/). يجب على المستخدمين أيضًا إزالة `IEventListener` الخاص بهم من [`EventTarget`](../../aspose.svg.dom/eventtarget/) بعد الانتهاء من استخدام المستمع.

```csharp
public interface IEventListener
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [HandleEvent](../../aspose.svg.dom.events/ieventlistener/handleevent/)(*[Event](../event/)*) | يتم استدعاء هذه الطريقة كلما حدث حدث من النوع الذي تم تسجيل واجهة `IEventListener` من أجله. |

## ملاحظات

عند نسخ Node باستخدام طريقة cloneNode لا يتم إرفاق مستمعي الأحداث المرتبطين بـ Node المصدر إلى Node المنسوخ. إذا رغب المستخدم في إضافة نفس مستمعي الأحداث إلى النسخة التي تم إنشاؤها حديثًا، يجب على المستخدم إضافتها يدويًا.

### انظر أيضًا

* namespace [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../)
