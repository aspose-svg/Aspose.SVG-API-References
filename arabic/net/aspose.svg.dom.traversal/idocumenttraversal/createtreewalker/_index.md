---
title: "IDocumentTraversal.CreateTreeWalker"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة IDocumentTraversal CreateTreeWalker. أنشئ TreeWalker جديدًا على الشجرة الفرعية التي جذورها العقدة المحددة"
type: docs
weight: 20
url: /ar/net/aspose.svg.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/)*) {#createtreewalker}

إنشاء TreeWalker جديد فوق الشجرة الفرعية المتجذرة في العقدة المحددة.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| root | Node | العقدة التي ستعمل كجذر لـ TreeWalker. لا يتم أخذ أعلام whatToShow و NodeFilter في الاعتبار عند تعيين هذه القيمة؛ سيتم قبول أي نوع عقدة كجذر. يتم تهيئة currentNode الخاص بـ TreeWalker إلى هذه العقدة، سواء كانت مرئية أم لا. يعمل الجذر كنقطة توقف لطرق التجوال التي تنظر إلى الأعلى في بنية المستند، مثل parentNode و nextNode. يجب ألا يكون الجذر فارغًا (null). |

### قيمة الإرجاع

TreeWalker الذي تم إنشاؤه حديثًا.

### انظر أيضًا

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/), long*) {#createtreewalker_1}

إنشاء TreeWalker جديد فوق الشجرة الفرعية المتجذرة في العقدة المحددة.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| root | Node | العقدة التي ستعمل كجذر لـ TreeWalker. لا يتم أخذ أعلام whatToShow و NodeFilter في الاعتبار عند تعيين هذه القيمة؛ سيتم قبول أي نوع عقدة كجذر. يتم تهيئة currentNode الخاص بـ TreeWalker إلى هذه العقدة، سواء كانت مرئية أم لا. يعمل الجذر كنقطة توقف لطرق التجوال التي تنظر إلى الأعلى في بنية المستند، مثل parentNode و nextNode. يجب ألا يكون الجذر فارغًا (null). |
| whatToShow | Int64 | العلم يحدد أنواع العقد التي قد تظهر في العرض المنطقي للشجرة التي يقدمها الـ tree-walker. راجع وصف NodeFilter للحصول على مجموعة القيم الممكنة لـ SHOW_. يمكن دمج هذه العلامات باستخدام OR. |

### قيمة الإرجاع

TreeWalker الذي تم إنشاؤه حديثًا.

### انظر أيضًا

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../../aspose.svg.dom/node/), long, [INodeFilter](../../inodefilter/)*) {#createtreewalker_2}

إنشاء TreeWalker جديد فوق الشجرة الفرعية المتجذرة في العقدة المحددة.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| root | Node | العقدة التي ستعمل كجذر لـ TreeWalker. لا يتم أخذ أعلام whatToShow و NodeFilter في الاعتبار عند تعيين هذه القيمة؛ سيتم قبول أي نوع عقدة كجذر. يتم تهيئة currentNode الخاص بـ TreeWalker إلى هذه العقدة، سواء كانت مرئية أم لا. يعمل الجذر كنقطة توقف لطرق التجوال التي تنظر إلى الأعلى في بنية المستند، مثل parentNode و nextNode. يجب ألا يكون الجذر فارغًا (null). |
| whatToShow | Int64 | العلم يحدد أنواع العقد التي قد تظهر في العرض المنطقي للشجرة التي يقدمها الـ tree-walker. راجع وصف NodeFilter للحصول على مجموعة القيم الممكنة لـ SHOW_. يمكن دمج هذه العلامات باستخدام OR. |
| filter | INodeFilter | NodeFilter لاستخدامه مع هذا TreeWalker، أو null للإشارة إلى عدم وجود مرشح. |

### قيمة الإرجاع

TreeWalker الذي تم إنشاؤه حديثًا.

### انظر أيضًا

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
