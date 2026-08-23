---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "خاصية INodeIterator PointerBeforeReferenceNode. تحدد قيمة هذا العلم ما إذا كانت أطفال عقد مراجع الكيان مرئية للمُكرِّر. إذا كان false فسيتم رفضهم وكذلك سلالتهم. لاحظ أن هذا الرفض له أولوية على whatToShow والمرشح. كما لاحظ أن هذه هي الحالة الوحيدة حاليًا التي قد يرفض فيها NodeIterators شجرة فرعية كاملة بدلاً من تخطي العقد الفردية. لإنشاء عرض للمستند يحتوي على مراجع الكيان مُوسَّعة ولا يكشف عن عقدة مرجع الكيان نفسها، استخدم أعلام whatToShow لإخفاء عقدة مرجع الكيان واضبط expandEntityReferences إلى true عند إنشاء المُكرِّر. لإنشاء عرض للمستند يحتوي على عقد مراجع الكيان دون توسيع الكيان، استخدم أعلام whatToShow لإظهار عقدة مرجع الكيان واضبط expandEntityReferences إلى false"
type: docs
weight: 10
url: /ar/net/aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

تحدد قيمة هذه العلامة ما إذا كانت أبناء عقد مراجع الكيان مرئية للمكرّر. إذا كان false، فسيتم رفضهم وتابعينهم. لاحظ أن هذا الرفض له أولوية على whatToShow والمرشح. كما لاحظ أن هذه هي الحالة الوحيدة حاليًا التي قد يرفض فيها NodeIterators شجرة فرعية كاملة بدلاً من تخطي العقد الفردية. لإنشاء عرض للمستند يحتوي على مراجع كيان موسعة ولا يكشف عن عقدة مرجع الكيان نفسها، استخدم علامات whatToShow لإخفاء عقدة مرجع الكيان واضبط expandEntityReferences إلى true عند إنشاء المكرّر. لإنشاء عرض للمستند يحتوي على عقد مراجع كيان دون توسيع الكيان، استخدم علامات whatToShow لإظهار عقدة مرجع الكيان واضبط expandEntityReferences إلى false.

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` إذا [expand entity references]؛ وإلا `false`.

### انظر أيضًا

* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
