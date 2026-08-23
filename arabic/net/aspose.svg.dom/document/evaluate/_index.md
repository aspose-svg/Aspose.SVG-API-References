---
title: "Document.Evaluate"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Document Evaluate. تُقيم سلسلة تعبير XPath وتُرجع نتيجة من النوع المحدد إذا كان ذلك ممكنًا"
type: docs
weight: 950
url: /ar/net/aspose.svg.dom/document/evaluate/
---
## Document.Evaluate method

يقيم سلسلة تعبير XPath ويعيد نتيجة من النوع المحدد إذا كان ذلك ممكنًا.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| expression | String | سلسلة تعبير XPath التي سيتم تحليلها وتقييمها. |
| contextNode | Node | السياق هو عقدة السياق لتقييم هذا التعبير XPath. |
| المُحَلّ | IXPathNSResolver | يسمح المُحَلّ بترجمة جميع البادئات، بما في ذلك بادئة مساحة اسم XML، داخل تعبير XPath إلى عناوين URI لمساحات الاسم المناسبة. |
| type | XPathResultType | إذا تم تحديد نوع محدد، فسيتم إرجاع النتيجة كنوع مطابق. |
| result | كائن | تحدد النتيجة كائن نتيجة محدد يمكن إعادة استخدامه وإرجاعه بواسطة هذه الطريقة. |

### قيمة الإرجاع

نتيجة تقييم تعبير XPath.

### انظر أيضًا

* interface [IXPathResult](../../../aspose.svg.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.svg.dom.xpath/xpathresulttype/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
