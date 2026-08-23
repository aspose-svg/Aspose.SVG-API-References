---
title: "Document.CreateTreeWalker"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Document CreateTreeWalker. تنشئ TreeWalker جديدًا على الشجرة الفرعية المتجذرة في العقدة المحددة."
type: docs
weight: 940
url: /ar/net/aspose.svg.dom/document/createtreewalker/
---
## CreateTreeWalker(*[Node](../../node/)*) {#createtreewalker}

إنشاء TreeWalker جديد فوق الشجرة الفرعية المتجذرة في العقدة المحددة.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| root | Node | العقدة التي ستعمل كجذر لـ TreeWalker. لا يتم أخذ أعلام whatToShow و NodeFilter في الاعتبار عند تعيين هذه القيمة؛ سيتم قبول أي نوع عقدة كجذر. يتم تهيئة currentNode الخاص بـ TreeWalker إلى هذه العقدة، سواء كانت مرئية أم لا. يعمل الجذر كنقطة توقف لطرق التجوال التي تنظر إلى الأعلى في بنية المستند، مثل parentNode و nextNode. يجب ألا يكون الجذر فارغًا (null). |

### قيمة الإرجاع

TreeWalker الذي تم إنشاؤه حديثًا.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا كان الجذر المحدد null. |

### انظر أيضًا

* interface [ITreeWalker](../../../aspose.svg.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../node/), long*) {#createtreewalker_1}

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

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا كان الجذر المحدد null. |

### انظر أيضًا

* interface [ITreeWalker](../../../aspose.svg.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CreateTreeWalker(*[Node](../../node/), long, [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)*) {#createtreewalker_2}

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

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا كان الجذر المحدد null. |

### انظر أيضًا

* interface [ITreeWalker](../../../aspose.svg.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
