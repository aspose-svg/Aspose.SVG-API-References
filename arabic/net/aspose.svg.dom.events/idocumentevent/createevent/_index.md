---
title: "IDocumentEvent.CreateEvent"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة IDocumentEvent CreateEvent. تُنشئ حدثًا من نوع يدعمه التنفيذ"
type: docs
weight: 10
url: /ar/net/aspose.svg.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

ينشئ [`Event`](../../event/) من نوع يدعمه التنفيذ.

```csharp
public Event CreateEvent(string eventType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| eventType | String | معامل eventType يحدد نوع واجهة [`Event`](../../event/) التي سيتم إنشاؤها. إذا كانت واجهة [`Event`](../../event/) المحددة مدعومة من قبل التنفيذ، ستعيد هذه الطريقة [`Event`](../../event/) جديدًا من نوع الواجهة المطلوب. إذا كان من المقرر إرسال [`Event`](../../event/) عبر طريقة [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/)، يجب استدعاء طريقة [`InitEvent`](../../event/initevent/) المناسبة بعد الإنشاء لتهيئة قيم [`Event`](../../event/). |

### قيمة الإرجاع

الـ[`Event`](../../event/) الذي تم إنشاؤه حديثًا

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا لم يدعم التنفيذ نوع واجهة [`Event`](../../event/) المطلوبة |

### انظر أيضًا

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
