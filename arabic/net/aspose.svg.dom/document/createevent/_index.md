---
title: "Document.CreateEvent"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Document CreateEvent. تنشئ Event من نوع يدعمه التنفيذ"
type: docs
weight: 880
url: /ar/net/aspose.svg.dom/document/createevent/
---
## Document.CreateEvent method

ينشئ [`Event`](../../../aspose.svg.dom.events/event/) من نوع يدعمه التنفيذ.

```csharp
public Event CreateEvent(string eventType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| eventType | String | معامل eventType يحدد نوع واجهة [`Event`](../../../aspose.svg.dom.events/event/) التي سيتم إنشاؤها. إذا كانت واجهة [`Event`](../../../aspose.svg.dom.events/event/) المحددة مدعومة من قبل التنفيذ، فإن هذه الطريقة ستعيد [`Event`](../../../aspose.svg.dom.events/event/) جديدًا من نوع الواجهة المطلوب. إذا كان من المقرر إرسال [`Event`](../../../aspose.svg.dom.events/event/) عبر طريقة [`DispatchEvent`](../../../aspose.svg.dom.events/ieventtarget/dispatchevent/) يجب استدعاء طريقة [`InitEvent`](../../../aspose.svg.dom.events/event/initevent/) المناسبة بعد الإنشاء لتهيئة قيم [`Event`](../../../aspose.svg.dom.events/event/). |

### قيمة الإرجاع

الـ[`Event`](../../../aspose.svg.dom.events/event/) الذي تم إنشاؤه حديثًا

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا لم يدعم التنفيذ نوع واجهة [`Event`](../../../aspose.svg.dom.events/event/) المطلوبة |

### انظر أيضًا

* class [Event](../../../aspose.svg.dom.events/event/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
