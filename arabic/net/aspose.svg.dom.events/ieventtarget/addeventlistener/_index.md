---
title: "IEventTarget.AddEventListener"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة IEventTarget AddEventListener. تسمح هذه الطريقة بتسجيل مستمعي الأحداث على هدف الحدث."
type: docs
weight: 10
url: /ar/net/aspose.svg.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(*string, [IEventListener](../../ieventlistener/)*) {#addeventlistener}

تسمح هذه الطريقة بتسجيل مستمعي الأحداث على هدف الحدث.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| type | String | نوع الحدث الذي يقوم المستخدم بتسجيله. |
| مستمع | IEventListener | يأخذ واجهة تم تنفيذها من قبل المستخدم تحتوي على الطرق التي سيتم استدعاؤها عند حدوث الحدث. |

## ملاحظات

إذا تم إضافة [`IEventListener`](../../ieventlistener/) إلى [`EventTarget`](../../../aspose.svg.dom/eventtarget/) أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية ولكن قد يتم تفعيله في مرحلة لاحقة من تدفق الحدث، مثل مرحلة الفقاعات.

إذا تم تسجيل مستمعي أحداث متطابقين متعددين على نفس [`EventTarget`](../../../aspose.svg.dom/eventtarget/) بنفس المعلمات، فسيتم تجاهل النسخ المكررة. لا تتسبب في استدعاء [`IEventListener`](../../ieventlistener/) مرتين، وبما أنها تم تجاهلها فلا تحتاج إلى إزالتها باستخدام طريقة [`RemoveEventListener`](../removeeventlistener/).

### انظر أيضًا

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../ieventlistener/), bool*) {#addeventlistener_1}

تسمح هذه الطريقة بتسجيل مستمعي الأحداث على هدف الحدث.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| type | String | نوع الحدث الذي يقوم المستخدم بتسجيله. |
| مستمع | IEventListener | يأخذ واجهة تم تنفيذها من قبل المستخدم تحتوي على الطرق التي سيتم استدعاؤها عند حدوث الحدث. |
| useCapture | Boolean | إذا كانت true، فإن useCapture تشير إلى أن المستخدم يرغب في بدء الالتقاط. بعد بدء الالتقاط، سيتم إرسال جميع الأحداث من النوع المحدد إلى [`IEventListener`](../../ieventlistener/) المسجل قبل إرسالها إلى أي أهداف حدث تحتها في الشجرة. الأحداث التي ترتفع في الفقاعات عبر الشجرة لن تقوم بتفعيل [`IEventListener`](../../ieventlistener/) المخصص لاستخدام الالتقاط. |

## ملاحظات

إذا تم إضافة [`IEventListener`](../../ieventlistener/) إلى [`EventTarget`](../../../aspose.svg.dom/eventtarget/) أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية ولكن قد يتم تفعيله في مرحلة لاحقة من تدفق الحدث، مثل مرحلة الفقاعات.

إذا تم تسجيل مستمعي أحداث متطابقين متعددين على نفس [`EventTarget`](../../../aspose.svg.dom/eventtarget/) بنفس المعلمات، فسيتم تجاهل النسخ المكررة. لا تتسبب في استدعاء [`IEventListener`](../../ieventlistener/) مرتين، وبما أنها تم تجاهلها فلا تحتاج إلى إزالتها باستخدام طريقة [`RemoveEventListener`](../removeeventlistener/).

### انظر أيضًا

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
