---
title: "فئة MutationRecord"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Dom.Mutations.MutationRecord فئة. يمثل MutationRecord تعديلًا فرديًا في DOM. وهو الكائن الذي يُمرَّر إلى MutationObservers MutationCallback"
type: docs
weight: 3130
url: /ar/net/aspose.svg.dom.mutations/mutationrecord/
---
## MutationRecord class

يمثل MutationRecord تعديلًا فرديًا في DOM. وهو الكائن الذي يُمرَّر إلى [`MutationObserver`](../mutationobserver/)'s [`MutationCallback`](../mutationcallback/).

```csharp
public class MutationRecord : DOMObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AddedNodes](../../aspose.svg.dom.mutations/mutationrecord/addednodes/) { get; } | أرجع العقد المضافة. |
| [AttributeName](../../aspose.svg.dom.mutations/mutationrecord/attributename/) { get; } | يرجع الاسم المحلي للخاصية المتغيَّرة، وإلا يكون null. |
| [AttributeNamespace](../../aspose.svg.dom.mutations/mutationrecord/attributenamespace/) { get; } | يرجع مساحة الاسم للخاصية المتغيَّرة، وإلا يكون null. |
| [NextSibling](../../aspose.svg.dom.mutations/mutationrecord/nextsibling/) { get; } | أرجع الأخ التالي للعقد المضافة أو المُزالة، أو null. |
| [OldValue](../../aspose.svg.dom.mutations/mutationrecord/oldvalue/) { get; } | قيمة الإرجاع تعتمد على النوع. بالنسبة لـ "attributes"، تكون قيمة الخاصية المتغيَّرة قبل التغيير. بالنسبة لـ "characterData"، تكون بيانات العقدة المتغيَّرة قبل التغيير. بالنسبة لـ "childList"، تكون null. |
| [PreviousSibling](../../aspose.svg.dom.mutations/mutationrecord/previoussibling/) { get; } | يرجع الأخ السابق للعقد المضافة أو المُزالة، أو null. |
| [RemovedNodes](../../aspose.svg.dom.mutations/mutationrecord/removednodes/) { get; } | أرجع العقد المُزالة. |
| [Target](../../aspose.svg.dom.mutations/mutationrecord/target/) { get; } | يرجع العقدة التي أثَّر عليها التعديل، حسب النوع. بالنسبة لـ "attributes"، تكون العنصر الذي تغيرت خاصيته. بالنسبة لـ "characterData"، تكون عقدة CharacterData. بالنسبة لـ "childList"، تكون العقدة التي تغير أطفالها. |
| [Type](../../aspose.svg.dom.mutations/mutationrecord/type/) { get; } | يرجع "attributes" إذا كان تعديلًا على خاصية، "characterData" إذا كان تعديلًا على عقدة CharacterData و "childList" إذا كان تعديلًا على شجرة العقد. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |

### انظر أيضًا

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)
