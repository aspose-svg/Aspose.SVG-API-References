---
title: "Event.StopPropagation"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Event StopPropagation. تُستخدم طريقة StopPropagation لمنع انتشار إضافي للحدث أثناء تدفق الحدث."
type: docs
weight: 140
url: /ar/net/aspose.svg.dom.events/event/stoppropagation/
---
## Event.StopPropagation method

طريقة `StopPropagation` تُستخدم لمنع انتشار إضافي للحدث أثناء تدفق الحدث.

```csharp
public void StopPropagation()
```

## ملاحظات

إذا تم استدعاء هذه الطريقة من قبل أي [`IEventListener`](../../ieventlistener/) سيتوقف انتشار الحدث عبر الشجرة. سيكمل الحدث إرساله إلى جميع المستمعين على [`IEventTarget`](../../ieventtarget/) الحالي قبل أن يتوقف تدفق الحدث. يمكن استخدام هذه الطريقة في أي مرحلة من مراحل تدفق الحدث.

### انظر أيضًا

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
