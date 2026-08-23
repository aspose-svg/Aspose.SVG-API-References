---
title: "IXPathEvaluator.Evaluate"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة IXPathEvaluator Evaluate. تُقيّم سلسلة تعبير XPath وتُعيد نتيجة من النوع المحدد إذا كان ذلك ممكنًا."
type: docs
weight: 30
url: /ar/net/aspose.svg.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

يقيم سلسلة تعبير XPath ويعيد نتيجة من النوع المحدد إذا كان ذلك ممكنًا.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| expression | String | سلسلة تعبير XPath التي سيتم تحليلها وتقييمها. |
| contextNode | Node | `context` هو عقدة السياق لتقييم تعبير XPath هذا. إذا تم الحصول على [`IXPathEvaluator`](../) عن طريق تحويل [`Document`](../../../aspose.svg.dom/document/) فإن هذه العقدة يجب أن تكون مملوكة لنفس المستند ويجب أن تكون إما [`Document`](../../../aspose.svg.dom/document/)، [`Element`](../../../aspose.svg.dom/element/)، [`Attr`](../../../aspose.svg.dom/attr/)، [`Text`](../../../aspose.svg.dom/text/)، [`CDATASection`](../../../aspose.svg.dom/cdatasection/)، [`Comment`](../../../aspose.svg.dom/comment/)، [`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction/)، أو عقدة XPathNamespace. إذا كانت عقدة السياق هي [`Text`](../../../aspose.svg.dom/text/) أو [`CDATASection`](../../../aspose.svg.dom/cdatasection/)، فإن السياق يُفسَّر كالعقدة النصية المنطقية الكاملة كما يراها XPath، ما لم تكن العقدة فارغة ففي هذه الحالة قد لا تكون صالحة كسياق XPath. |
| resolver | IXPathNSResolver | `resolver` يسمح بترجمة جميع البادئات، بما في ذلك بادئة مساحة الاسم `xml`، داخل تعبير XPath إلى عناوين URI مناسبة للمساحات الاسمية. إذا تم تحديده كـ `null`، فإن أي بادئة مساحة اسم داخل التعبير ستؤدي إلى رمي [`DOMException`](../../../aspose.svg.dom/domexception/) مع الرمز `NAMESPACE_ERR`. |
| type | XPathResultType | إذا تم تحديد `type` معين، فستُعاد النتيجة كنوع مطابق. بالنسبة لنتائج XPath 1.0، يجب أن يكون هذا أحد قيم تعداد [`XPathResultType`](../../xpathresulttype/). |
| result | Object | الـ `result` يحدد كائن نتيجة محدد قد يُعاد استخدامه وتُعيده هذه الطريقة. إذا تم تحديده كـ `null` أو إذا لم تُعيد التنفيذ إعادة استخدام النتيجة المحددة، فسيتم إنشاء كائن نتيجة جديد وإرجاعه. بالنسبة لنتائج XPath 1.0، سيكون هذا الكائن من النوع [`IXPathResult`](../../ixpathresult/). |

### قيمة الإرجاع

نتيجة تقييم تعبير XPath. بالنسبة لنتائج XPath 1.0، سيكون هذا الكائن من النوع [`IXPathResult`](../../ixpathresult/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_EXPRESSION_ERR: يُرفع إذا كان التعبير غير قانوني وفقًا لقواعد [`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: يُرفع إذا تعذّر تحويل النتيجة لإرجاع النوع المحدد. |
| [DOMException](../../../aspose.svg.dom/domexception/) | NAMESPACE_ERR: يُرفع إذا كان التعبير يحتوي على بادئات مساحات اسمية لا يمكن حلها بواسطة [`IXPathNSResolver`](../../ixpathnsresolver/) المحدد. |
| [DOMException](../../../aspose.svg.dom/domexception/) | WRONG_DOCUMENT_ERR: العقدة من مستند غير مدعوم من قبل هذا [`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: العقدة ليست من النوع المسموح به كعقدة سياق XPath أو نوع الطلب غير مسموح به من قبل هذا [`IXPathEvaluator`](../). |

### انظر أيضًا

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
