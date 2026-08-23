---
title: "IEventTarget.DispatchEvent"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة IEventTarget DispatchEvent. تسمح هذه الطريقة بإرسال الأحداث إلى نموذج حدث التنفيذ."
type: docs
weight: 20
url: /ar/net/aspose.svg.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

تسمح هذه الطريقة بإرسال الأحداث إلى نموذج الأحداث الخاص بالتنفيذ.

```csharp
public bool DispatchEvent(Event @event)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| حدث | حدث | يحدد نوع الحدث والسلوك والمعلومات السياقية التي ستُستخدم في معالجة الحدث. |

### قيمة الإرجاع

قيمة الإرجاع لـ [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) تشير إلى ما إذا كان أي من المستمعين الذين عالجوا الحدث قد استدعوا [`PreventDefault`](../../event/preventdefault/). إذا تم استدعاء [`PreventDefault`](../../event/preventdefault/) تكون القيمة false، وإلا تكون القيمة true.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) |  |

## ملاحظات

الأحداث المرسلة بهذه الطريقة ستحصل على نفس سلوك الالتقاط والفقاعات كما في الأحداث المرسلة مباشرةً بواسطة التنفيذ. هدف الحدث هو [`EventTarget`](../../../aspose.svg.dom/eventtarget/) الذي يتم استدعاء [`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) عليه.

### انظر أيضًا

* class [Event](../../event/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
