---
title: "Aspose.Svg.Dom.Events"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "مساحة الأسماء Aspose.Svg.Dom.Events تُوفر كائنات لأي أحداث متعلقة بتحديث DOM. تشمل الاشتراك في ملاحظة معلومات سياقية محددة مرتبطة بالحدث بالإضافة إلى إنشاء أحداث مخصصة."
type: docs
weight: 100
url: /ar/net/aspose.svg.dom.events/
---
مساحة الاسم **Aspose.Svg.Dom.Events** توفر كائنات لأي أحداث تتعلق بتحديث الـ DOM. تشمل الاشتراك في ملاحظة معلومات سياقية محددة مرتبطة بالحدث بالإضافة إلى إنشاء أحداث مخصصة.

## الفئات

| الفئة | الوصف |
| --- | --- |
| [CustomEvent](./customevent/) | يمكن استخدام الأحداث عبر واجهة CustomEvent لنقل بيانات مخصصة. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | الحدث [`DocumentLoadErrorEvent`](../aspose.svg.dom.events/documentloaderrorevent/) يحدث عندما لا يكون المورد المطلوب متاحاً. |
| [DOMEventHandler](./domeventhandler/) | يمثّل رد النداء لمعالجة الحدث. |
| [ErrorEvent](./errorevent/) | الحدث [`ErrorEvent`](../aspose.svg.dom.events/errorevent/) يُوفر معلومات سياقية حول الأخطاء التي حدثت أثناء وقت التشغيل. |
| [Event](./event/) | الحدث [`Event`](../aspose.svg.dom.events/event/) يُستخدم لتوفير معلومات سياقية حول حدث للمعالج الذي يعالج الحدث. |
| [FocusEvent](./focusevent/) | واجهة FocusEvent تُوفر معلومات سياقية محددة مرتبطة بأحداث التركيز. |
| [InputEvent](./inputevent/) | يتم إرسال أحداث الإدخال كإشعارات كلما تم تحديث DOM. |
| [KeyboardEvent](./keyboardevent/) | واجهة KeyboardEvent تُوفر معلومات سياقية محددة مرتبطة بأجهزة لوحة المفاتيح. كل حدث لوحة مفاتيح يشير إلى مفتاح باستخدام قيمة. عادةً ما تُوجه أحداث لوحة المفاتيح إلى العنصر الذي يملك التركيز. |
| [MouseEvent](./mouseevent/) | واجهة MouseEvent تُوفر معلومات سياقية محددة مرتبطة بأحداث الفأرة. |
| [UIEvent](./uievent/) | واجهة UIEvent تُوفر معلومات سياقية محددة مرتبطة بأحداث واجهة المستخدم. |
| [WheelEvent](./wheelevent/) | واجهة WheelEvent تُوفر معلومات سياقية محددة مرتبطة بأحداث العجلة. لإنشاء مثال من واجهة WheelEvent، استخدم مُنشئ WheelEvent، مع تمرير قاموس WheelEventInit اختياري. |
## الواجهات

| واجهة | الوصف |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | الواجهة [`IDocumentEvent`](../aspose.svg.dom.events/idocumentevent/) تُوفر آلية يمكن للمستخدم من خلالها إنشاء [`Event`](../aspose.svg.dom.events/event/) من نوع مدعوم من قبل التنفيذ. |
| [IEventListener](./ieventlistener/) | The واجهة [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) هي الطريقة الأساسية لمعالجة الأحداث. يقوم المستخدمون بتنفيذ واجهة [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) وتسجيل المستمع الخاص بهم على [`EventTarget`](../aspose.svg.dom/eventtarget/) باستخدام طريقة [`AddEventListener`](../aspose.svg.dom/eventtarget/addeventlistener/). يجب على المستخدمين أيضًا إزالة [`IEventListener`](../aspose.svg.dom.events/ieventlistener/) من [`EventTarget`](../aspose.svg.dom/eventtarget/) بعد الانتهاء من استخدام المستمع. |
| [IEventTarget](./ieventtarget/) | The واجهة [`EventTarget`](../aspose.svg.dom/eventtarget/) يتم تنفيذها من قبل جميع العقد في تنفيذ يدعم نموذج أحداث DOM. لذلك، يمكن الحصول على هذه الواجهة باستخدام طرق التحويل الخاصة بالربط على مثال من واجهة العقدة. تسمح الواجهة بتسجيل وإزالة مستمعي الأحداث على [`EventTarget`](../aspose.svg.dom/eventtarget/) وإرسال الأحداث إلى ذلك [`IEventTarget`](../aspose.svg.dom.events/ieventtarget/). |
