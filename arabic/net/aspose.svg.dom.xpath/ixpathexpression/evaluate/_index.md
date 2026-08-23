---
title: "IXPathExpression.Evaluate"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Evaluate في IXPathExpression. تقيم هذا التعبير XPath وتعيد نتيجة"
type: docs
weight: 10
url: /ar/net/aspose.svg.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

يقوم بتقييم هذا التعبير XPath ويعيد نتيجة.

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| contextNode | Node | الـ `context` هو عقدة السياق لتقييم هذا التعبير XPath. إذا تم الحصول على [`IXPathEvaluator`](../../ixpathevaluator/) عن طريق تحويل [`Document`](../../../aspose.svg.dom/document/) فإن هذا يجب أن يكون مملوكاً لنفس المستند ويجب أن يكون إما [`Document`](../../../aspose.svg.dom/document/), [`Element`](../../../aspose.svg.dom/element/), [`Attr`](../../../aspose.svg.dom/attr/), [`Text`](../../../aspose.svg.dom/text/), [`CDATASection`](../../../aspose.svg.dom/cdatasection/), [`Comment`](../../../aspose.svg.dom/comment/), [`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction/), أو عقدة XPathNamespace. إذا كانت عقدة السياق هي [`Text`](../../../aspose.svg.dom/text/) أو [`CDATASection`](../../../aspose.svg.dom/cdatasection/), فسيتم تفسير السياق ككل عقدة نصية منطقية كما يراها XPath، ما لم تكن العقدة فارغة في هذه الحالة قد لا تُستخدم كالسياق XPath. |
| type | XPathResultType | إذا تم تحديد `type` معين، فسيتم تحويل النتيجة لإرجاع النوع المحدد بالاعتماد على تحويلات XPath وستفشل إذا لم يكن التحويل المطلوب ممكنًا. يجب أن يكون هذا أحد قيم [`XPathResultType`](../../xpathresulttype/). |
| result | Object | الـ `result` يحدد كائن نتيجة محدد قد يُعاد استخدامه وتُعيده هذه الطريقة. إذا تم تحديده كـ `null` أو إذا لم تُعيد التنفيذ إعادة استخدام النتيجة المحددة، فسيتم إنشاء كائن نتيجة جديد وإرجاعه. بالنسبة لنتائج XPath 1.0، سيكون هذا الكائن من النوع [`IXPathResult`](../../ixpathresult/). |

### قيمة الإرجاع

نتيجة تقييم تعبير XPath. بالنسبة لنتائج XPath 1.0، سيكون هذا الكائن من النوع [`IXPathResult`](../../ixpathresult/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: يُرفع إذا تعذّر تحويل النتيجة لإرجاع النوع المحدد. |
| [DOMException](../../../aspose.svg.dom/domexception/) | WRONG_DOCUMENT_ERR: العقدة من مستند غير مدعوم من قبل [`IXPathEvaluator`](../../ixpathevaluator/) الذي أنشأ هذه [`IXPathExpression`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: العقدة ليست من النوع المسموح به كعقدة سياق XPath أو نوع الطلب غير مسموح به من قبل هذه [`IXPathExpression`](../). |

### انظر أيضًا

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.svg.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
