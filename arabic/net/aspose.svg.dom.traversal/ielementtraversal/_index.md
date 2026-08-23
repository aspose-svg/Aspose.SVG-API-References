---
title: "واجهة IElementTraversal"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Dom.Traversal.IElementTraversal interface. واجهة ElementTraversal هي مجموعة من السمات للقراءة فقط التي تسمح للمؤلف بالتنقل بسهولة بين العناصر في المستند. في تطبيقات Element Traversal المتوافقة، يجب على جميع الكائنات التي تنفّذ Element أيضًا تنفيذ واجهة ElementTraversal."
type: docs
weight: 3230
url: /ar/net/aspose.svg.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

واجهة ElementTraversal هي مجموعة من السمات للقراءة فقط تسمح للمؤلف بالتنقل بسهولة بين العناصر في المستند. في تطبيقات Element Traversal المتوافقة، يجب على جميع الكائنات التي تنفّذ Element أن تنفّذ أيضاً واجهة ElementTraversal.

```csharp
public interface IElementTraversal
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ChildElementCount](../../aspose.svg.dom.traversal/ielementtraversal/childelementcount/) { get; } | يعيد العدد الحالي لعقد العناصر التي هي أبناء هذا العنصر. 0 إذا لم يكن لهذا العنصر أي عقدة فرعية من نوع nodeType 1. |
| [FirstElementChild](../../aspose.svg.dom.traversal/ielementtraversal/firstelementchild/) { get; } | يعيد أول عقدة عنصر فرعي لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر فرعية. |
| [LastElementChild](../../aspose.svg.dom.traversal/ielementtraversal/lastelementchild/) { get; } | يعيد عقدة العنصر الطفل الأخير لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر طفل. |
| [NextElementSibling](../../aspose.svg.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | يعيد عقدة العنصر الشقيقة التالية لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة عنصر تأتي بعده في شجرة المستند. |
| [PreviousElementSibling](../../aspose.svg.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | يعيد عقدة العنصر الشقيقة السابقة لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة عنصر تأتي قبلها في شجرة المستند. |

### انظر أيضًا

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
