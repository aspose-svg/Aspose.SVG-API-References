---
title: InitEvent
second_title: Aspose.SVG لمرجع .NET API
description: ملفInitEventaspose.svg.dom.events/event/initevent يتم استخدام طريقة لتهيئة قيمةEventaspose.svg.dom.events/event تم إنشاؤه من خلال IDocumentEventaspose.svg.dom.events/idocumentevent الواجهة .
type: docs
weight: 110
url: /ar/net/aspose.svg.dom.events/event/initevent/
---
## Event.InitEvent method

ملف`InitEvent` يتم استخدام طريقة لتهيئة قيمة[`Event`](../../event) تم إنشاؤه من خلال [`IDocumentEvent`](../../idocumentevent) الواجهة .

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| type | String | نوع الحدث. |
| bubbles | Boolean | إذا تم التعيين على`حقيقي` [فقاعات]. |
| cancelable | Boolean | إذا تم التعيين على`حقيقي` [قابل للإلغاء]. |

### ملاحظات

لا يمكن استدعاء هذه الطريقة إلا قبل إرسال الحدث عبر[`DispatchEvent`](../../ieventtarget/dispatchevent) الطريقة ، على الرغم من أنه قد يتم استدعاؤها عدة مرات خلال تلك المرحلة إذا لزم الأمر. إذا تم استدعاؤها عدة مرات ، يكون للطلب النهائي الأسبقية. لم تتغير.

### أنظر أيضا

* class [Event](../../event)
* مساحة الاسم [Aspose.Svg.Dom.Events](../../event)
* المجسم [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->