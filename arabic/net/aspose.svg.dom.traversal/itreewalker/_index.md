---
title: "واجهة ITreeWalker"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Dom.Traversal.ITreeWalker interface. تُستخدم كائنات TreeWalker للتنقل في شجرة المستند أو شجرة فرعية باستخدام عرض المستند المحدد بواسطة أعلام whatToShow والفلتر إذا كان موجودًا. أي دالة تقوم بالتنقل باستخدام TreeWalker ستدعم تلقائيًا أي عرض معرف بواسطة TreeWalker."
type: docs
weight: 3270
url: /ar/net/aspose.svg.dom.traversal/itreewalker/
---
## ITreeWalker interface

تُستخدم كائنات TreeWalker للتنقل في شجرة المستند أو شجرتها الفرعية باستخدام عرض المستند المحدد بأعلام whatToShow والفلتر (إن وجد). أي دالة تقوم بالتنقل باستخدام TreeWalker ستدعم تلقائيًا أي عرض يُحدَّد بواسطة TreeWalker.

إزالة العقد من العرض المنطقي لشجرة فرعية يمكن أن ينتج بنية تختلف اختلافًا كبيرًا عن نفس الشجرة الفرعية في المستند الكامل غير المفلتر. قد تكون العقد التي هي أخوة في عرض TreeWalker أطفالًا لعقد مختلفة، مفصولة على مسافات واسعة في العرض الأصلي. على سبيل المثال، اعتبر NodeFilter يتخطى جميع العقد باستثناء عقد النص والعقدة الجذرية للمستند. في العرض المنطقي الناتج، ستكون جميع عقد النص أخوة وتظهر كأطفال مباشرة للعقدة الجذرية، بغض النظر عن عمق بنية المستند الأصلي.

انظر أيضًا إلى [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface ITreeWalker : ITraversal
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CurrentNode](../../aspose.svg.dom.traversal/itreewalker/currentnode/) { get; set; } | العقدة التي يقع فيها TreeWalker حاليًا. قد تتسبب التعديلات على شجرة DOM في عدم قبول العقدة الحالية بواسطة الفلتر المرتبط بـ TreeWalker. يمكن أيضًا تعيين currentNode صراحةً إلى أي عقدة، سواء كانت ضمن الشجرة الفرعية المحددة بالعقدة الجذرية أو لا، أو ما إذا كانت ستُقبل بواسطة الفلتر وأعلام whatToShow. تستمر traversals الإضافية بالنسبة إلى currentNode حتى وإن لم تكن جزءًا من العرض الحالي، عن طريق تطبيق الفلاتر في الاتجاه المطلوب؛ إذا لم يكن هناك إمكانية للتنقل، لا يتم تغيير currentNode. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [FirstChild](../../aspose.svg.dom.traversal/itreewalker/firstchild/)() | ينقل TreeWalker إلى أول طفل مرئي للعقدة الحالية، ويعيد العقدة الجديدة. إذا لم تكن للعقدة الحالية أطفال مرئيون، يُعيد null، ويحتفظ بالعقدة الحالية. |
| [LastChild](../../aspose.svg.dom.traversal/itreewalker/lastchild/)() | ينقل TreeWalker إلى آخر طفل مرئي للعقدة الحالية، ويعيد العقدة الجديدة. إذا لم تكن للعقدة الحالية أطفال مرئيون، يُعيد null، ويحتفظ بالعقدة الحالية. |
| [NextNode](../../aspose.svg.dom.traversal/itreewalker/nextnode/)() | ينقل TreeWalker إلى العقدة المرئية التالية بترتيب المستند بالنسبة إلى العقدة الحالية، ويعيد العقدة الجديدة. إذا لم تكن للعقدة الحالية عقدة تالية، أو إذا حاول البحث عن nextNode الصعود من العقدة الجذرية لـ TreeWalker، يُعيد null، ويحتفظ بالعقدة الحالية. |
| [NextSibling](../../aspose.svg.dom.traversal/itreewalker/nextsibling/)() | ينقل TreeWalker إلى الأخ الأصغر التالي للعقدة الحالية، ويعيد العقدة الجديدة. إذا لم يكن للعقدة الحالية أخ مرئي التالي، يُعيد null، ويحتفظ بالعقدة الحالية. |
| [ParentNode](../../aspose.svg.dom.traversal/itreewalker/parentnode/)() | ينقل إلى ويعيد أقرب عقدة سلف مرئية للعقدة الحالية. إذا حاول البحث عن parentNode الصعود من عقدة الجذر الخاصة بـ TreeWalker، أو إذا فشل في العثور على عقدة سلف مرئية، فإن هذه الطريقة تحتفظ بالموقع الحالي وتعيد null. |
| [PreviousNode](../../aspose.svg.dom.traversal/itreewalker/previousnode/)() | ينقل TreeWalker إلى العقدة المرئية السابقة في ترتيب المستند بالنسبة للعقدة الحالية، ويعيد العقدة الجديدة. إذا لم تكن للعقدة الحالية عقدة سابقة، أو إذا حاول البحث عن previousNode الصعود من عقدة جذر TreeWalker، يعيد null، ويحتفظ بالعقدة الحالية. |
| [PreviousSibling](../../aspose.svg.dom.traversal/itreewalker/previoussibling/)() | ينقل TreeWalker إلى الأخ السابق للعقدة الحالية، ويعيد العقدة الجديدة. إذا لم يكن للعقدة الحالية أخ مرئي سابق، يعيد null، ويحتفظ بالعقدة الحالية. |

### انظر أيضًا

* interface [ITraversal](../itraversal/)
* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
