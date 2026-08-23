---
title: "واجهة IXPathResult"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "واجهة Aspose.Svg.Dom.XPath.IXPathResult. تمثل واجهة XPathResult نتيجة تقييم تعبير XPath 1.0 ضمن سياق عقدة معينة. بما أن تقييم تعبير XPath يمكن أن ينتج أنواعًا مختلفة من النتائج، يتيح هذا الكائن إمكانية اكتشاف ومعالجة نوع وقيمة النتيجة."
type: docs
weight: 3350
url: /ar/net/aspose.svg.dom.xpath/ixpathresult/
---
## IXPathResult interface

واجهة `XPathResult` تمثل نتيجة تقييم تعبير XPath 1.0 ضمن سياق عقدة معينة. بما أن تقييم تعبير XPath يمكن أن ينتج أنواعًا متعددة من النتائج، يتيح هذا الكائن إمكانية اكتشاف وتعديل نوع وقيمة النتيجة.

```csharp
public interface IXPathResult
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BooleanValue](../../aspose.svg.dom.xpath/ixpathresult/booleanvalue/) { get; } | قيمة هذه النتيجة المنطقية. |
| [InvalidIteratorState](../../aspose.svg.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | يشير إلى أن المتكرر أصبح غير صالح. صحيح إذا كان `resultType` من النوع `UnorderedNodeIterator` أو `OrderedNodeIterator` وتم تعديل المستند منذ إرجاع هذه النتيجة. |
| [NumberValue](../../aspose.svg.dom.xpath/ixpathresult/numbervalue/) { get; } | قيمة هذه النتيجة الرقمية. |
| [ResultType](../../aspose.svg.dom.xpath/ixpathresult/resulttype/) { get; } | رمز يمثل نوع هذه النتيجة، كما هو معرف في http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult enum [`XPathResultType`](../xpathresulttype/). |
| [SingleNodeValue](../../aspose.svg.dom.xpath/ixpathresult/singlenodevalue/) { get; } | قيمة نتيجة العقدة المفردة هذه، والتي قد تكون `null`. |
| [SnapshotLength](../../aspose.svg.dom.xpath/ixpathresult/snapshotlength/) { get; } | عدد العقد في لقطة النتيجة. القيم الصالحة لمؤشرات snapshotItem هي من `0` إلى `snapshotLength-1` شاملًا. |
| [StringValue](../../aspose.svg.dom.xpath/ixpathresult/stringvalue/) { get; } | قيمة هذه النتيجة النصية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [IterateNext](../../aspose.svg.dom.xpath/ixpathresult/iteratenext/)() | يتكرر ويعيد العقدة التالية من مجموعة العقد أو `null` إذا لم يتبق أي عقد. |
| [SnapshotItem](../../aspose.svg.dom.xpath/ixpathresult/snapshotitem/)(*int*) | يعيد العنصر رقم `index` في مجموعة اللقطة. إذا كان `index` أكبر من أو يساوي عدد العقد في القائمة، فإن هذه الطريقة تعيد `null`. على عكس نتيجة المتكرر، لا تصبح اللقطة غير صالحة، ولكن قد لا تتطابق مع المستند الحالي إذا تم تغييره. |

### انظر أيضًا

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
