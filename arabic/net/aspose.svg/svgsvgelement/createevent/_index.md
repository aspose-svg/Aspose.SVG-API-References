---
title: "SVGSVGElement.CreateEvent"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGSVGElement CreateEvent. تُنشئ كائن Event من نوع يدعمه التنفيذ."
type: docs
weight: 110
url: /ar/net/aspose.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

ينشئ [`Event`](../../../aspose.svg.dom.events/event/) من نوع يدعمه التنفيذ.

```csharp
public Event CreateEvent(string eventType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| eventType | String | معامل eventType يحدد نوع واجهة [`Event`](../../../aspose.svg.dom.events/event/) التي سيتم إنشاؤها. إذا كانت واجهة [`Event`](../../../aspose.svg.dom.events/event/) المحددة مدعومة من قبل التنفيذ، فإن هذه الطريقة ستُرجع كائنًا جديدًا من نوع [`Event`](../../../aspose.svg.dom.events/event/) المطلوب. إذا كان من المقرر إرسال [`Event`](../../../aspose.svg.dom.events/event/) عبر طريقة [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/)، يجب استدعاء طريقة [`InitEvent`](../../../aspose.svg.dom.events/event/initevent/) المناسبة بعد الإنشاء لتهيئة قيم [`Event`](../../../aspose.svg.dom.events/event/). |

### قيمة الإرجاع

الـ[`Event`](../../../aspose.svg.dom.events/event/) الذي تم إنشاؤه حديثًا

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا لم يدعم التنفيذ نوع واجهة [`Event`](../../../aspose.svg.dom.events/event/) المطلوبة |

### انظر أيضًا

* class [Event](../../../aspose.svg.dom.events/event/)
* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
