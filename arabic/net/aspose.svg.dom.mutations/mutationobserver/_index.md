---
title: Class MutationObserver
second_title: Aspose.SVG لمرجع .NET API
description: Aspose.Svg.Dom.Mutations.MutationObserver فصل. أMutationObserver يمكن استخدام الكائن لمراقبة الطفرات في شجرةNode .
type: docs
weight: 1120
url: /ar/net/aspose.svg.dom.mutations/mutationobserver/
---
## MutationObserver class

أ`MutationObserver` يمكن استخدام الكائن لمراقبة الطفرات في شجرة[`Node`](../../aspose.svg.dom/node/) .

```csharp
public class MutationObserver : DOMObject
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | إنشاء كائن MutationObserver وتعيين[`MutationCallback`](../mutationcallback/) لمعاودة الاتصال. يتم استدعاء رد الاتصال بقائمة كائنات MutationRecord كوسيطة أولى وكائن MutationObserver المركب كوسيطة ثانية. يتم استدعاؤه بعد العقد المسجلة مع!:Observe(Node, IMutationObserverInit) طريقة متحورة. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Disconnect](../../aspose.svg.dom.mutations/mutationobserver/disconnect/)() | توقف المراقب عن ملاحظة أي طفرات. حتى يتم استخدام طريقة الملاحظة () مرة أخرى ، لن يتم استدعاء رد اتصال المراقب. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | تُستخدم هذه الطريقة لاسترداد كائن ECMAScriptType . |
| [Observe](../../aspose.svg.dom.mutations/mutationobserver/observe/#observe)(Node) | يوجه وكيل المستخدم لملاحظة هدف معين (عقدة) والإبلاغ عن أي طفرات بناءً على المعايير التي تقدمها الخيارات (كائن) . تسمح وسيطة الخيارات بتعيين خيارات ملاحظة الطفرات عبر أعضاء الكائن. |
| [Observe](../../aspose.svg.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | يوجه وكيل المستخدم لملاحظة هدف معين (عقدة) والإبلاغ عن أي طفرات بناءً على المعايير التي تقدمها الخيارات (كائن) . تسمح وسيطة الخيارات بتعيين خيارات ملاحظة الطفرات عبر أعضاء الكائن. |
| [TakeRecords](../../aspose.svg.dom.mutations/mutationobserver/takerecords/)() | تقوم الطريقة بإرجاع نسخة من قائمة انتظار السجل ثم إفراغ قائمة انتظار التسجيل. |

### أنظر أيضا

* class [DOMObject](../../aspose.svg.dom/domobject/)
* مساحة الاسم [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* المجسم [Aspose.SVG](../../)


