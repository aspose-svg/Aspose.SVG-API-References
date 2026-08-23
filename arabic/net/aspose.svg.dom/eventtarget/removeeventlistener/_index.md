---
title: "EventTarget.RemoveEventListener"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة EventTarget RemoveEventListener. تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تمت إزالة IEventListener من EventTarget أثناء معالجة حدث، فلن يتم تفعيله بالإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتهم"
type: docs
weight: 50
url: /ar/net/aspose.svg.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(*string, [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/), bool*) {#removeeventlistener}

تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تمت إزالة [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) من [`EventTarget`](../) أثناء معالجة حدث، فلن يتم تفعيله بالإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتهم.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| type | String | يحدد نوع الحدث لـ [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) الذي يتم إزالته. |
| handler | DOMEventHandler | المعلمة [`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/) تشير إلى [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) الذي سيتم إزالته. |
| useCapture | Boolean | يحدد ما إذا كان EventListener الذي يتم إزالته مسجلاً كمستمع التقاط أم لا. إذا تم تسجيل مستمع مرتين، أحدهما مع التقاط والآخر بدون، يجب إزالة كل منهما بشكل منفصل. إزالة مستمع التقاط لا تؤثر على نسخة غير ملتقطة من نفس المستمع، والعكس صحيح. |

### انظر أيضًا

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)*) {#removeeventlistener_1}

تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تمت إزالة [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) من [`EventTarget`](../) أثناء معالجة حدث، فلن يتم تفعيله بالإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتهم.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| type | String | يحدد نوع الحدث لـ [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) الذي يتم إزالته. |
| listener | IEventListener | المُعامل [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) يشير إلى [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) الذي سيُزال. |

### انظر أيضًا

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/), bool*) {#removeeventlistener_2}

تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تمت إزالة [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) من [`EventTarget`](../) أثناء معالجة حدث، فلن يتم تفعيله بالإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتهم.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| type | String | يحدد نوع الحدث لـ [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) الذي يتم إزالته. |
| listener | IEventListener | المُعامل [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) يشير إلى [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) الذي سيُزال. |
| useCapture | Boolean | يحدد ما إذا كان EventListener الذي يتم إزالته مسجلاً كمستمع التقاط أم لا. إذا تم تسجيل مستمع مرتين، أحدهما مع التقاط والآخر بدون، يجب إزالة كل منهما بشكل منفصل. إزالة مستمع التقاط لا تؤثر على نسخة غير ملتقطة من نفس المستمع، والعكس صحيح. |

### انظر أيضًا

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
