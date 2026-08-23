---
title: "ITreeWalker.ParentNode"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة ITreeWalker ParentNode. تنتقل إلى أقرب عقدة سلف مرئية للعقدة الحالية وتعيدها. إذا حاول البحث عن parentNode الصعود من عقدة الجذر للـ TreeWalker أو إذا فشل في العثور على عقدة سلف مرئية، يحتفظ هذا الأسلوب بالموقع الحالي ويعيد null."
type: docs
weight: 60
url: /ar/net/aspose.svg.dom.traversal/itreewalker/parentnode/
---
## ITreeWalker.ParentNode method

ينقل إلى ويعيد أقرب عقدة سلف مرئية للعقدة الحالية. إذا حاول البحث عن parentNode الصعود من عقدة الجذر الخاصة بـ TreeWalker، أو إذا فشل في العثور على عقدة سلف مرئية، فإن هذه الطريقة تحتفظ بالموقع الحالي وتعيد null.

```csharp
public Node ParentNode()
```

### قيمة الإرجاع

العقدة الأصلية الجديدة، أو null إذا لم تكن للعقدة الحالية أصل في العرض المنطقي للـ TreeWalker.

### انظر أيضًا

* class [Node](../../../aspose.svg.dom/node/)
* interface [ITreeWalker](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
