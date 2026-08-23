---
title: "IEventTarget.RemoveEventListener"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة IEventTarget RemoveEventListener. تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة IEventListener من EventTarget أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتهم."
type: docs
weight: 30
url: /ar/net/aspose.svg.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(*string, [IEventListener](../../ieventlistener/)*) {#removeeventlistener}

تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة [`IEventListener`](../../ieventlistener/) من [`EventTarget`](../../../aspose.svg.dom/eventtarget/) أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتهم.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| type | String | يحدد نوع الحدث الخاص بـ [`IEventListener`](../../ieventlistener/) الذي يتم إزالته. |
| listener | IEventListener | معامل [`IEventListener`](../../ieventlistener/) يشير إلى [`IEventListener`](../../ieventlistener/) الذي سيتم إزالته. |

### انظر أيضًا

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../ieventlistener/), bool*) {#removeeventlistener_1}

تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة [`IEventListener`](../../ieventlistener/) من [`EventTarget`](../../../aspose.svg.dom/eventtarget/) أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتهم.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| type | String | يحدد نوع الحدث الخاص بـ [`IEventListener`](../../ieventlistener/) الذي يتم إزالته. |
| listener | IEventListener | معامل [`IEventListener`](../../ieventlistener/) يشير إلى [`IEventListener`](../../ieventlistener/) الذي سيتم إزالته. |
| useCapture | Boolean | يحدد ما إذا كان EventListener الذي يتم إزالته مسجلاً كمستمع التقاط أم لا. إذا تم تسجيل مستمع مرتين، أحدهما مع التقاط والآخر بدون، يجب إزالة كل منهما بشكل منفصل. إزالة مستمع التقاط لا تؤثر على نسخة غير ملتقطة من نفس المستمع، والعكس صحيح. |

### انظر أيضًا

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
