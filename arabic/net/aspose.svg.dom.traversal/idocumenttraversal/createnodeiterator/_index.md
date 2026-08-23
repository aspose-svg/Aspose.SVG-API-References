---
title: "IDocumentTraversal.CreateNodeIterator"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة IDocumentTraversal CreateNodeIterator. أنشئ NodeIterator جديدًا على الشجرة الفرعية التي جذورها العقدة المحددة"
type: docs
weight: 10
url: /ar/net/aspose.svg.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(*[Node](../../../aspose.svg.dom/node/)*) {#createnodeiterator}

إنشاء NodeIterator جديد على الشجرة الفرعية التي جذورها العقدة المحددة.

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| root | Node | العقدة التي سيتم تكرارها مع أبنائها. يتم وضع المؤشر في البداية مباشرةً قبل هذه العقدة. لا يتم أخذ علامات whatToShow والمرشح، إن وجد، في الاعتبار عند تعيين هذا الموضع. يجب ألا يكون الجذر null. |

### قيمة الإرجاع

NodeIterator الذي تم إنشاؤه حديثًا.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا كان الجذر المحدد null. |

### انظر أيضًا

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../../aspose.svg.dom/node/), long*) {#createnodeiterator_1}

إنشاء NodeIterator جديد على الشجرة الفرعية التي جذورها العقدة المحددة.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| root | Node | العقدة التي سيتم تكرارها مع أبنائها. يتم وضع المؤشر في البداية مباشرةً قبل هذه العقدة. لا يتم أخذ علامات whatToShow والمرشح، إن وجد، في الاعتبار عند تعيين هذا الموضع. يجب ألا يكون الجذر null. |
| whatToShow | Int64 | العلم يحدد أي أنواع العقد قد تظهر في العرض المنطقي للشجرة التي يقدمها المتكرر. راجع وصف NodeFilter للحصول على مجموعة القيم الممكنة لـ SHOW_. يمكن دمج هذه العلامات باستخدام OR. |

### قيمة الإرجاع

NodeIterator الذي تم إنشاؤه حديثًا.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا كان الجذر المحدد null. |

### انظر أيضًا

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateNodeIterator(*[Node](../../../aspose.svg.dom/node/), long, [INodeFilter](../../inodefilter/)*) {#createnodeiterator_2}

إنشاء NodeIterator جديد على الشجرة الفرعية التي جذورها العقدة المحددة.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| root | Node | العقدة التي سيتم تكرارها مع أبنائها. يتم وضع المؤشر في البداية مباشرةً قبل هذه العقدة. لا يتم أخذ علامات whatToShow والمرشح، إن وجد، في الاعتبار عند تعيين هذا الموضع. يجب ألا يكون الجذر null. |
| whatToShow | Int64 | العلم يحدد أي أنواع العقد قد تظهر في العرض المنطقي للشجرة التي يقدمها المتكرر. راجع وصف NodeFilter للحصول على مجموعة القيم الممكنة لـ SHOW_. يمكن دمج هذه العلامات باستخدام OR. |
| filter | INodeFilter | NodeFilter لاستخدامه مع هذا TreeWalker، أو null للإشارة إلى عدم وجود مرشح. |

### قيمة الإرجاع

NodeIterator الذي تم إنشاؤه حديثًا.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا كان الجذر المحدد null. |

### انظر أيضًا

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
