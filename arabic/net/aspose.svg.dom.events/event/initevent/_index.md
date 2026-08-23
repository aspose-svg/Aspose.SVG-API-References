---
title: "Event.InitEvent"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Event InitEvent. تُستخدم طريقة InitEvent لتهيئة قيمة حدث تم إنشاؤه عبر واجهة IDocumentEvent"
type: docs
weight: 110
url: /ar/net/aspose.svg.dom.events/event/initevent/
---
## Event.InitEvent method

طريقة `InitEvent` تُستخدم لتهيئة قيمة [`Event`](../) تم إنشاؤه عبر واجهة [`IDocumentEvent`](../../idocumentevent/).

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| type | String | نوع الحدث. |
| bubbles | Boolean | إذا تم تعيينه إلى `true` [bubbles]. |
| cancelable | Boolean | إذا تم تعيينه إلى `true` [cancelable]. |

## ملاحظات

يمكن استدعاء هذه الطريقة فقط قبل أن يتم إرسال الحدث عبر طريقة [`DispatchEvent`](../../ieventtarget/dispatchevent/)، على الرغم من أنه يمكن استدعاؤها عدة مرات خلال تلك المرحلة إذا لزم الأمر. إذا تم الاستدعاء عدة مرات فإن الاستدعاء الأخير له أولوية. إذا تم الاستدعاء من فئة فرعية لواجهة Event فإن القيم المحددة في طريقة initEvent هي التي تُعدَّل، وتُترك جميع السمات الأخرى دون تغيير.

### انظر أيضًا

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
