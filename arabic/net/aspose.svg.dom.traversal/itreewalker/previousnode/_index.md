---
title: "ITreeWalker.PreviousNode"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة ITreeWalker PreviousNode. تنقل الـ TreeWalker إلى العقدة المرئية السابقة في ترتيب المستند بالنسبة إلى العقدة الحالية وتعيد العقدة الجديدة. إذا لم تكن للعقدة الحالية عقدة سابقة أو إذا حاول البحث عن previousNode الصعود من عقدة الجذر للـ TreeWalker تُعيد null وتبقي على العقدة الحالية."
type: docs
weight: 70
url: /ar/net/aspose.svg.dom.traversal/itreewalker/previousnode/
---
## ITreeWalker.PreviousNode method

ينقل TreeWalker إلى العقدة المرئية السابقة في ترتيب المستند بالنسبة للعقدة الحالية، ويعيد العقدة الجديدة. إذا لم تكن للعقدة الحالية عقدة سابقة، أو إذا حاول البحث عن previousNode الصعود من عقدة جذر TreeWalker، يعيد null، ويحتفظ بالعقدة الحالية.

```csharp
public Node PreviousNode()
```

### قيمة الإرجاع

العقدة الجديدة، أو null إذا لم تكن للعقدة الحالية عقدة سابقة في العرض المنطقي للـ TreeWalker.

### انظر أيضًا

* class [Node](../../../aspose.svg.dom/node/)
* interface [ITreeWalker](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
