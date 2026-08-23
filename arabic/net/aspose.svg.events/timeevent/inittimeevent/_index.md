---
title: "TimeEvent.InitTimeEvent"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة InitTimeEvent في TimeEvent. تُستخدم طريقة initTimeEvent لتهيئة قيمة TimeEvent تم إنشاؤها عبر واجهة DocumentEvent. لا يمكن استدعاء هذه الطريقة إلا قبل أن يتم إرسال TimeEvent عبر طريقة dispatchEvent، على الرغم من أنه يمكن استدعاؤها عدة مرات خلال تلك المرحلة إذا لزم الأمر. إذا تم استدعاؤها عدة مرات، فإن الاستدعاء النهائي له أولوية."
type: docs
weight: 30
url: /ar/net/aspose.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

يُستخدم الأسلوب initTimeEvent لتهيئة قيمة TimeEvent تم إنشاؤه عبر واجهة DocumentEvent. لا يمكن استدعاء هذا الأسلوب إلا قبل أن يتم إرسال TimeEvent عبر الأسلوب dispatchEvent، رغم أنه قد يُستدعى عدة مرات خلال تلك المرحلة إذا لزم الأمر. إذا تم استدعاؤه عدة مرات، فإن الاستدعاء النهائي له أولوية.

```csharp
public void InitTimeEvent(string typeArg, IAbstractView viewArg, long detailArg)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| typeArg | String | يحدد نوع الحدث. |
| viewArg | IAbstractView | يحدد AbstractView للحدث. |
| detailArg | Int64 | يحدد تفاصيل الحدث. |

### انظر أيضًا

* interface [IAbstractView](../../../aspose.svg.dom.views/iabstractview/)
* class [TimeEvent](../)
* namespace [Aspose.Svg.Events](../../../aspose.svg.events/)
* assembly [Aspose.SVG](../../../)
