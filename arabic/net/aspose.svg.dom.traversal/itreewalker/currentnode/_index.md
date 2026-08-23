---
title: "ITreeWalker.CurrentNode"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "خاصية ITreeWalker CurrentNode. العقدة التي يتموضع عندها الـ TreeWalker حالياً. قد تتسبب التعديلات على شجرة DOM في عدم قبول العقدة الحالية من قبل الفلتر المرتبط بالـ TreeWalker. يمكن أيضاً تعيين currentNode صراحةً إلى أي عقدة سواء كانت ضمن الشجرة الفرعية المحددة بواسطة عقدة الجذر أو لا، أو ما إذا كانت ستُقبل بواسطة الفلتر وعلامات whatToShow. تستمر عملية التجوال الإضافية بالنسبة إلى currentNode حتى وإن لم تكن جزءاً من العرض الحالي عن طريق تطبيق الفلاتر في الاتجاه المطلوب؛ إذا لم يكن هناك إمكانية للتجوال لا يتم تغيير currentNode."
type: docs
weight: 10
url: /ar/net/aspose.svg.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

العقدة التي يقع فيها TreeWalker حاليًا. قد تتسبب التعديلات على شجرة DOM في عدم قبول العقدة الحالية بواسطة الفلتر المرتبط بـ TreeWalker. يمكن أيضًا تعيين currentNode صراحةً إلى أي عقدة، سواء كانت ضمن الشجرة الفرعية المحددة بالعقدة الجذرية أو لا، أو ما إذا كانت ستُقبل بواسطة الفلتر وأعلام whatToShow. تستمر traversals الإضافية بالنسبة إلى currentNode حتى وإن لم تكن جزءًا من العرض الحالي، عن طريق تطبيق الفلاتر في الاتجاه المطلوب؛ إذا لم يكن هناك إمكانية للتنقل، لا يتم تغيير currentNode.

```csharp
public Node CurrentNode { get; set; }
```

### Property Value

العقدة الحالية.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا تم محاولة تعيين currentNode إلى null. |

### انظر أيضًا

* class [Node](../../../aspose.svg.dom/node/)
* interface [ITreeWalker](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
