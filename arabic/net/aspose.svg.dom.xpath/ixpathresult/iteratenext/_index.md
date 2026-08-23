---
title: "IXPathResult.IterateNext"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة IXPathResult IterateNext. تتنقل وتعيد العقدة التالية من مجموعة العقد أو `null` إذا لم يتبق أي عقد."
type: docs
weight: 80
url: /ar/net/aspose.svg.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

يتكرر ويعيد العقدة التالية من مجموعة العقد أو `null` إذا لم يتبق أي عقد.

```csharp
public Node IterateNext()
```

### قيمة الإرجاع

يعيد العقدة التالية.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: يُرفع إذا لم يكن `resultType` من نوع `UnorderedNodeIterator` أو `OrderedNodeIterator`. |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR: تم تعديل المستند منذ إرجاع النتيجة. |

### انظر أيضًا

* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathResult](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
