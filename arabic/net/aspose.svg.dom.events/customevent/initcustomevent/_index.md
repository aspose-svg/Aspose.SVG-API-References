---
title: "CustomEvent.InitCustomEvent"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "CustomEvent InitCustomEvent method. /// تُستخدم طريقة InitEvent لتهيئة قيمة حدث تم إنشاؤه عبر واجهة IDocumentEvent"
type: docs
weight: 30
url: /ar/net/aspose.svg.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// تُستخدم طريقة [`InitEvent`](../../event/initevent/) لتهيئة قيمة [`Event`](../../event/) تم إنشاؤه عبر واجهة [`IDocumentEvent`](../../idocumentevent/).

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| type | String | نوع الحدث. |
| bubbles | Boolean | إذا تم تعيينه إلى `true` [bubbles]. |
| cancelable | Boolean | إذا تم تعيينه إلى `true` [cancelable]. |
| detail | كائن | البيانات المخصصة. |

## ملاحظات

يمكن استدعاء هذه الطريقة فقط قبل أن يتم إرسال الحدث عبر طريقة [`DispatchEvent`](../../ieventtarget/dispatchevent/)، على الرغم من أنه يمكن استدعاؤها عدة مرات خلال تلك المرحلة إذا لزم الأمر. إذا تم الاستدعاء عدة مرات فإن الاستدعاء الأخير له أولوية. إذا تم الاستدعاء من فئة فرعية لواجهة Event فإن القيم المحددة في طريقة initEvent هي التي تُعدَّل، وتُترك جميع السمات الأخرى دون تغيير.

### انظر أيضًا

* class [CustomEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
