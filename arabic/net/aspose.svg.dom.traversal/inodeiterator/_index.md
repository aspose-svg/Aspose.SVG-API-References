---
title: "واجهة INodeIterator"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "واجهة Aspose.Svg.Dom.Traversal.INodeIterator. تُستخدم المكررات للانتقال عبر مجموعة من العقد مثل مجموعة العقد في NodeList، أو شجرة المستند الفرعية التي يتحكم فيها عقدة معينة، أو نتائج استعلام أو أي مجموعة أخرى من العقد. تُحدد مجموعة العقد التي سيتم تكرارها بواسطة تنفيذ NodeIterator. يحدد DOM Level 2 تنفيذًا واحدًا لـ NodeIterator لتجوال شجرة المستند الفرعية بترتيب المستند. تُنشأ مثيلات هذه المكررات عن طريق استدعاء DocumentTraversal.createNodeIterator"
type: docs
weight: 3250
url: /ar/net/aspose.svg.dom.traversal/inodeiterator/
---
## INodeIterator interface

تُستخدم المكررات للانتقال عبر مجموعة من العقد، مثل مجموعة العقد في NodeList، الشجرة الفرعية للمستند التي تحكمها عقدة معينة، نتائج استعلام، أو أي مجموعة أخرى من العقد. تُحدَّد مجموعة العقد التي ستُكرر بواسطة تنفيذ NodeIterator. يحدد DOM المستوى 2 تنفيذًا واحدًا لـ NodeIterator لتصفح شجرة المستند بترتيب المستند. تُنشأ مثيلات هذه المكررات عن طريق استدعاء DocumentTraversal .createNodeIterator().

انظر أيضًا إلى [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface INodeIterator : ITraversal
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | تحدد قيمة هذه العلامة ما إذا كانت أبناء عقد مراجع الكيان مرئية للمكرّر. إذا كان false، فسيتم رفضهم وتابعينهم. لاحظ أن هذا الرفض له أولوية على whatToShow والمرشح. كما لاحظ أن هذه هي الحالة الوحيدة حاليًا التي قد يرفض فيها NodeIterators شجرة فرعية كاملة بدلاً من تخطي العقد الفردية. لإنشاء عرض للمستند يحتوي على مراجع كيان موسعة ولا يكشف عن عقدة مرجع الكيان نفسها، استخدم علامات whatToShow لإخفاء عقدة مرجع الكيان واضبط expandEntityReferences إلى true عند إنشاء المكرّر. لإنشاء عرض للمستند يحتوي على عقد مراجع كيان دون توسيع الكيان، استخدم علامات whatToShow لإظهار عقدة مرجع الكيان واضبط expandEntityReferences إلى false. |
| [ReferenceNode](../../aspose.svg.dom.traversal/inodeiterator/referencenode/) { get; } | عقدة المرجع الحالية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Detach](../../aspose.svg.dom.traversal/inodeiterator/detach/)() | يفصل الـ NodeIterator عن المجموعة التي كان يتنقل خلالها، مطلقًا أي موارد حسابية ومُضعِفًا المتتبع في الحالة INVALID. بعد استدعاء الفاصل، ستؤدي الاستدعاءات إلى nextNode أو previousNode إلى رفع الاستثناء INVALID_STATE_ERR. |
| [NextNode](../../aspose.svg.dom.traversal/inodeiterator/nextnode/)() | يعيد العقدة التالية في المجموعة ويُحسّن موضع المتتبع في المجموعة. بعد إنشاء NodeIterator، تُعيد الاستدعاءة الأولى إلى nextNode() العقدة الأولى في المجموعة. |
| [PreviousNode](../../aspose.svg.dom.traversal/inodeiterator/previousnode/)() | يعيد العقدة السابقة في المجموعة وينقل موضع NodeIterator إلى الخلف في المجموعة. |

### انظر أيضًا

* interface [ITraversal](../itraversal/)
* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
