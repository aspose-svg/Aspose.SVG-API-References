---
title: "واجهة IDocumentTraversal"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "واجهة Aspose.Svg.Dom.Traversal.IDocumentTraversal. يحتوي DocumentTraversal على طرق تنشئ المكررات و tree-walkers لتجوال عقدة وأطفالها بترتيب المستند بطريقة عمق أولاً (pre-order) وهو ما يعادل الترتيب الذي تظهر فيه وسوم البداية في تمثيل النص للمستند. في DOMs التي تدعم ميزة Traversal، سيتم تنفيذ DocumentTraversal بواسطة نفس الكائنات التي تنفذ واجهة Document."
type: docs
weight: 3220
url: /ar/net/aspose.svg.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

يحتوي DocumentTraversal على أساليب تُنشئ المكررات ومُتجولات الشجرة لتصفح عقدة وأطفالها بترتيب المستند (التصفح بعمق أولاً، التصفح قبل الترتيب، وهو ما يعادل الترتيب الذي تظهر فيه وسوم البداية في تمثيل النص للمستند). في DOMs التي تدعم ميزة Traversal، سيتم تنفيذ DocumentTraversal بواسطة نفس الكائنات التي تنفّذ واجهة Document.

انظر أيضًا إلى [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface IDocumentTraversal
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(*[Node](../../aspose.svg.dom/node/)*) | إنشاء NodeIterator جديد على الشجرة الفرعية التي جذورها العقدة المحددة. |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(*[Node](../../aspose.svg.dom/node/), long*) | إنشاء NodeIterator جديد على الشجرة الفرعية التي جذورها العقدة المحددة. |
| [CreateNodeIterator](../../aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(*[Node](../../aspose.svg.dom/node/), long, [INodeFilter](../inodefilter/)*) | إنشاء NodeIterator جديد على الشجرة الفرعية التي جذورها العقدة المحددة. |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(*[Node](../../aspose.svg.dom/node/)*) | إنشاء TreeWalker جديد فوق الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(*[Node](../../aspose.svg.dom/node/), long*) | إنشاء TreeWalker جديد فوق الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [CreateTreeWalker](../../aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(*[Node](../../aspose.svg.dom/node/), long, [INodeFilter](../inodefilter/)*) | إنشاء TreeWalker جديد فوق الشجرة الفرعية المتجذرة في العقدة المحددة. |

### انظر أيضًا

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
