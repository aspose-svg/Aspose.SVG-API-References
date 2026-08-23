---
title: "EventTarget.AddEventListener"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة EventTarget AddEventListener. تُعد دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف"
type: docs
weight: 20
url: /ar/net/aspose.svg.dom/eventtarget/addeventlistener/
---
## AddEventListener(*string, [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/), bool*) {#addeventlistener}

يضبط دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف.

يعمل عن طريق إضافة دالة أو كائن ينفّذ [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/), إلى قائمة مستمعي الأحداث لنوع الحدث المحدد على [`EventTarget`](../) الذي يُستدعى عليه. إذا كانت الدالة أو الكائن موجودة بالفعل في قائمة مستمعي الأحداث لهذا الهدف، فلن تُضاف مرة ثانية.

```csharp
public void AddEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| type | String | نوع الحدث الذي يقوم المستخدم بتسجيله. |
| handler | DOMEventHandler | يأخذ [`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler/) ليتم استدعاؤه عندما يحدث الحدث. |
| useCapture | Boolean | إذا كان true، فإن useCapture يشير إلى أن المستخدم يرغب في بدء الالتقاط. بعد بدء الالتقاط، سيتم إرسال جميع الأحداث من النوع المحدد إلى [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) المسجل قبل إرسالها إلى أي أهداف حدث تحتها في الشجرة. الأحداث التي ترتفع صعودًا عبر الشجرة لن تُفعّل [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) المخصص لاستخدام الالتقاط. |

## ملاحظات

إذا تم إضافة [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) إلى [`EventTarget`](../) أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية ولكن قد يتم تفعيله في مرحلة لاحقة من تدفق الحدث، مثل مرحلة الفقاعات.

إذا تم تسجيل مستمعي أحداث متطابقين متعددين على نفس [`EventTarget`](../) بنفس المعلمات، فسيتم تجاهل النسخ المكررة. لا تتسبب في استدعاء [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) مرتين، وبما أنها تم تجاهلها فلا حاجة لإزالتها باستخدام طريقة [`RemoveEventListener`](../removeeventlistener/).

### انظر أيضًا

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)*) {#addeventlistener_1}

يضبط دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف.

يعمل عن طريق إضافة دالة أو كائن ينفّذ [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/), إلى قائمة مستمعي الأحداث لنوع الحدث المحدد على [`EventTarget`](../) الذي يُستدعى عليه. إذا كانت الدالة أو الكائن موجودة بالفعل في قائمة مستمعي الأحداث لهذا الهدف، فلن تُضاف مرة ثانية.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| type | String | نوع الحدث الذي يقوم المستخدم بتسجيله. |
| مستمع | IEventListener | يأخذ واجهة تم تنفيذها من قبل المستخدم تحتوي على الطرق التي سيتم استدعاؤها عند حدوث الحدث. |

## ملاحظات

إذا تم إضافة [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) إلى [`EventTarget`](../) أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية ولكن قد يتم تفعيله في مرحلة لاحقة من تدفق الحدث، مثل مرحلة الفقاعات.

إذا تم تسجيل مستمعي أحداث متطابقين متعددين على نفس [`EventTarget`](../) بنفس المعلمات، فسيتم تجاهل النسخ المكررة. لا تتسبب في استدعاء [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) مرتين، وبما أنها تم تجاهلها فلا حاجة لإزالتها باستخدام طريقة [`RemoveEventListener`](../removeeventlistener/).

### انظر أيضًا

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## AddEventListener(*string, [IEventListener](../../../aspose.svg.dom.events/ieventlistener/), bool*) {#addeventlistener_2}

يضبط دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف.

يعمل عن طريق إضافة دالة أو كائن ينفّذ [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/), إلى قائمة مستمعي الأحداث لنوع الحدث المحدد على [`EventTarget`](../) الذي يُستدعى عليه. إذا كانت الدالة أو الكائن موجودة بالفعل في قائمة مستمعي الأحداث لهذا الهدف، فلن تُضاف مرة ثانية.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| type | String | نوع الحدث الذي يقوم المستخدم بتسجيله. |
| مستمع | IEventListener | يأخذ واجهة تم تنفيذها من قبل المستخدم تحتوي على الطرق التي سيتم استدعاؤها عند حدوث الحدث. |
| useCapture | Boolean | إذا كان true، فإن useCapture يشير إلى أن المستخدم يرغب في بدء الالتقاط. بعد بدء الالتقاط، سيتم إرسال جميع الأحداث من النوع المحدد إلى [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) المسجل قبل إرسالها إلى أي أهداف حدث تحتها في الشجرة. الأحداث التي ترتفع صعودًا عبر الشجرة لن تُفعّل [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) المخصص لاستخدام الالتقاط. |

## ملاحظات

إذا تم إضافة [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) إلى [`EventTarget`](../) أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية ولكن قد يتم تفعيله في مرحلة لاحقة من تدفق الحدث، مثل مرحلة الفقاعات.

إذا تم تسجيل مستمعي أحداث متطابقين متعددين على نفس [`EventTarget`](../) بنفس المعلمات، فسيتم تجاهل النسخ المكررة. لا تتسبب في استدعاء [`IEventListener`](../../../aspose.svg.dom.events/ieventlistener/) مرتين، وبما أنها تم تجاهلها فلا حاجة لإزالتها باستخدام طريقة [`RemoveEventListener`](../removeeventlistener/).

### انظر أيضًا

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
