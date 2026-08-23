---
title: "واجهة IParentNode"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "واجهة Aspose.Svg.Dom.IParentNode. تُعرّف واجهة IParentNode التي يتم تنفيذها من قبل أي آباء محتملين."
type: docs
weight: 3080
url: /ar/net/aspose.svg.dom/iparentnode/
---
## IParentNode interface

يعرّف واجهة `IParentNode` التي يتم تنفيذها من قبل أي آباء محتملين.

```csharp
public interface IParentNode : IElementTraversal
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ChildElementCount](../../aspose.svg.dom/iparentnode/childelementcount/) { get; } | يجب أن تُعيد خاصية childElementCount عدد الأطفال لكائن السياق الذين هم عناصر. |
| [Children](../../aspose.svg.dom/iparentnode/children/) { get; } | يعيد العناصر الفرعية. |
| [FirstElementChild](../../aspose.svg.dom/iparentnode/firstelementchild/) { get; } | تُعيد الطفل الأول الذي يكون عنصرًا، وإلا تُعيد null. |
| [LastElementChild](../../aspose.svg.dom/iparentnode/lastelementchild/) { get; } | تُعيد الطفل الأخير الذي يكون عنصرًا، وإلا تُعيد null. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [QuerySelector](../../aspose.svg.dom/iparentnode/queryselector/)(*string*) | تُعيد العنصر الأول الذي هو تابع للـ node ويتطابق مع المحددات. |
| [QuerySelectorAll](../../aspose.svg.dom/iparentnode/queryselectorall/)(*string*) | تُعيد جميع العناصر التابعة للـ node والتي تتطابق مع المحددات. |

### انظر أيضًا

* interface [IElementTraversal](../../aspose.svg.dom.traversal/ielementtraversal/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
