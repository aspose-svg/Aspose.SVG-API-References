---
title: EventTarget.RemoveEventListener
second_title: Aspose.SVG لمرجع .NET API
description: EventTarget طريقة. تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كانIEventListener تمت إزالته من ملفEventTarget أثناء معالجة حدث  لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها.
type: docs
weight: 40
url: /ar/net/aspose.svg.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(string, DOMEventHandler, bool) {#removeeventlistener}

تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) تمت إزالته من ملف[`EventTarget`](../) أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| type | String | يحدد نوع حدث[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) يتم إزالتها. |
| handler | DOMEventHandler | ال[`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/) تشير المعلمة إلى[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) ليتم إزالتها. |
| useCapture | Boolean | يحدد ما إذا كان EventListener الذي يتم إزالته قد تم تسجيله كمستمع ملتقط أم لا. من نفس المستمع والعكس صحيح. |

### أنظر أيضا

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* مساحة الاسم [Aspose.Svg.Dom](../../eventtarget/)
* المجسم [Aspose.SVG](../../../)

---

## RemoveEventListener(string, IEventListener) {#removeeventlistener_1}

تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) تمت إزالته من ملف[`EventTarget`](../) أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| type | String | يحدد نوع حدث[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) يتم إزالتها. |
| listener | IEventListener | ال[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) تشير المعلمة إلى[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) ليتم إزالتها. |

### أنظر أيضا

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* مساحة الاسم [Aspose.Svg.Dom](../../eventtarget/)
* المجسم [Aspose.SVG](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_2}

تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) تمت إزالته من ملف[`EventTarget`](../) أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| type | String | يحدد نوع حدث[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) يتم إزالتها. |
| listener | IEventListener | ال[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) تشير المعلمة إلى[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) ليتم إزالتها. |
| useCapture | Boolean | يحدد ما إذا كان EventListener الذي يتم إزالته قد تم تسجيله كمستمع ملتقط أم لا. من نفس المستمع والعكس صحيح. |

### أنظر أيضا

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* مساحة الاسم [Aspose.Svg.Dom](../../eventtarget/)
* المجسم [Aspose.SVG](../../../)


