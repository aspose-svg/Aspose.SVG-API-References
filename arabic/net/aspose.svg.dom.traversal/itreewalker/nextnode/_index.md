---
title: "ITreeWalker.NextNode"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة ITreeWalker NextNode. تنقل الـ TreeWalker إلى العقدة المرئية التالية في ترتيب المستند بالنسبة إلى العقدة الحالية وتعيد العقدة الجديدة. إذا لم تكن للعقدة الحالية عقدة تالية أو إذا حاول البحث عن nextNode الصعود من عقدة الجذر للـ TreeWalker تُعيد null وتبقي على العقدة الحالية."
type: docs
weight: 40
url: /ar/net/aspose.svg.dom.traversal/itreewalker/nextnode/
---
## ITreeWalker.NextNode method

ينقل TreeWalker إلى العقدة المرئية التالية بترتيب المستند بالنسبة إلى العقدة الحالية، ويعيد العقدة الجديدة. إذا لم تكن للعقدة الحالية عقدة تالية، أو إذا حاول البحث عن nextNode الصعود من العقدة الجذرية لـ TreeWalker، يُعيد null، ويحتفظ بالعقدة الحالية.

```csharp
public Node NextNode()
```

### قيمة الإرجاع

العقدة الجديدة، أو null إذا لم تكن للعقدة الحالية عقدة تالية في العرض المنطقي للـ TreeWalker.

### انظر أيضًا

* class [Node](../../../aspose.svg.dom/node/)
* interface [ITreeWalker](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
