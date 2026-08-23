---
title: "IXPathResult.SnapshotItem"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة IXPathResult SnapshotItem. تُعيد العنصر رقم الفهرس في مجموعة اللقطات. إذا كان الفهرس أكبر من أو يساوي عدد العقد في القائمة تُعيد هذه الطريقة `null`. على عكس نتيجة المتكرر، لا تصبح اللقطة غير صالحة ولكن قد لا تتطابق مع المستند الحالي إذا تم تغييره"
type: docs
weight: 90
url: /ar/net/aspose.svg.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

يعيد العنصر رقم `index` في مجموعة اللقطة. إذا كان `index` أكبر من أو يساوي عدد العقد في القائمة، فإن هذه الطريقة تعيد `null`. على عكس نتيجة المتكرر، لا تصبح اللقطة غير صالحة، ولكن قد لا تتطابق مع المستند الحالي إذا تم تغييره.

```csharp
public Node SnapshotItem(int index)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| index | Int32 | فهرس في مجموعة اللقطات. |

### قيمة الإرجاع

العقدة في الموضع `index` في `NodeList`، أو `null` إذا لم يكن ذلك فهرسًا صالحًا.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: يُرفع إذا لم يكن `resultType` من نوع `UnorderedNodeSnapshot` أو `OrderedNodeSnapshot`. |

### انظر أيضًا

* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathResult](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
