---
title: "فئة MutationObserver"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Dom.Mutations.MutationObserver فئة. يمكن استخدام كائن MutationObserver لمراقبة التعديلات على شجرة Node"
type: docs
weight: 3110
url: /ar/net/aspose.svg.dom.mutations/mutationobserver/
---
## MutationObserver class

يمكن استخدام كائن `MutationObserver` لمراقبة التعديلات على شجرة [`Node`](../../aspose.svg.dom/node/).

```csharp
public class MutationObserver : DOMObject
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [MutationObserver](mutationobserver/)(*[MutationCallback](../mutationcallback/)*) | ينشئ كائن MutationObserver ويضبط [`MutationCallback`](../mutationcallback/) الخاص به إلى callback. يتم استدعاء الـ callback مع قائمة من كائنات MutationRecord كوسيط أول وكائن MutationObserver المُنشأ كوسيط ثانٍ. يتم استدعاؤه بعد أن تُعدَّل العقد المسجَّلة باستخدام طريقة [`Observe`](./observe/). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Disconnect](../../aspose.svg.dom.mutations/mutationobserver/disconnect/)() | يوقف المراقب عن مراقبة أي تعديلات. حتى يتم استدعاء طريقة observe() مرة أخرى، لن يتم استدعاء callback الخاص بالمراقب. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [Observe](../../aspose.svg.dom.mutations/mutationobserver/observe/#observe)(*[Node](../../aspose.svg.dom/node/)*) | يُعطي تعليمات لوكيل المستخدم لمراقبة هدف معين (عقدة) والإبلاغ عن أي تعديلات بناءً على المعايير المحددة في options (كائن). يسمح معامل options بتعيين خيارات مراقبة التعديلات عبر أعضاء الكائن. |
| [Observe](../../aspose.svg.dom.mutations/mutationobserver/observe/#observe_1)(*[Node](../../aspose.svg.dom/node/), [MutationObserverInit](../mutationobserverinit/)*) | يُعطي تعليمات لوكيل المستخدم لمراقبة هدف معين (عقدة) والإبلاغ عن أي تعديلات بناءً على المعايير المحددة في options (كائن). يسمح معامل options بتعيين خيارات مراقبة التعديلات عبر أعضاء الكائن. |
| [TakeRecords](../../aspose.svg.dom.mutations/mutationobserver/takerecords/)() | ترجع الطريقة نسخة من طابور السجلات ثم تُفرغ طابور السجلات. |

### انظر أيضًا

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)
