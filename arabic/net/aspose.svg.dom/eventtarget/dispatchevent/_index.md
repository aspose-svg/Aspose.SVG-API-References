---
title: "EventTarget.DispatchEvent"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة EventTarget DispatchEvent. تُرسل حدثًا إلى IEventTarget المحدد بشكل متزامن مع استدعاء مستمعي الأحداث المتأثرين بالترتيب المناسب. تنطبق قواعد معالجة الأحداث العادية بما في ذلك مرحلة الالتقاط والفقاعة الاختيارية أيضًا على الأحداث التي تُرسل يدويًا باستخدام DispatchEvent"
type: docs
weight: 30
url: /ar/net/aspose.svg.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

يُرسل حدثًا إلى [`IEventTarget`](../../../aspose.svg.dom.events/ieventtarget/)، (متزامنًا) مع استدعاء مستمعي الأحداث المتأثرين بالترتيب المناسب. تنطبق قواعد معالجة الأحداث العادية (بما في ذلك مرحلة الالتقاط والفقاعة الاختيارية) أيضًا على الأحداث التي تُرسل يدويًا باستخدام [`DispatchEvent`](../../../aspose.svg.dom.events/ieventtarget/dispatchevent/).

```csharp
public bool DispatchEvent(Event @event)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| حدث | حدث | يحدد نوع الحدث والسلوك والمعلومات السياقية التي ستُستخدم في معالجة الحدث. |

### قيمة الإرجاع

قيمة الإرجاع لـ `DispatchEvent` تشير إلى ما إذا كان أي من المستمعين الذين عالجوا الحدث قد استدعوا [`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault/). إذا تم استدعاء [`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault/) تكون القيمة false، وإلا تكون القيمة true.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../domexception/) |  |

## ملاحظات

الأحداث التي تُرسل بهذه الطريقة ستحظى بنفس سلوك الالتقاط والفقاعة كما الأحداث التي تُرسل مباشرةً بواسطة التنفيذ. هدف الحدث هو [`EventTarget`](../) الذي يُستدعى عليه `DispatchEvent`.

### انظر أيضًا

* class [Event](../../../aspose.svg.dom.events/event/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
