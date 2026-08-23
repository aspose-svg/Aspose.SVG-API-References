---
title: "IXPathEvaluator.CreateExpression"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة IXPathEvaluator CreateExpression. تُنشئ تعبير XPath مُحلل مع مساحات اسمية محلولة. هذا مفيد عندما يُعاد استخدام التعبير في تطبيق لأنه يجعل من الممكن تجميع سلسلة التعبير إلى شكل داخلي أكثر كفاءة وإعادة حل جميع بادئات المساحات الاسمية التي تظهر داخل التعبير."
type: docs
weight: 10
url: /ar/net/aspose.svg.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

ينشئ تعبير XPath محلل مع مساحات أسماء محلولة. هذا مفيد عندما سيتم إعادة استخدام التعبير في تطبيق لأنه يجعل من الممكن تجميع سلسلة التعبير إلى شكل داخلي أكثر كفاءة وإعادة حل جميع مسافات أسماء البادئات التي تظهر داخل التعبير.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| expression | String | سلسلة تعبير XPath التي سيتم تحليلها. |
| resolver | IXPathNSResolver | `resolver` يسمح بترجمة جميع البادئات، بما في ذلك بادئة مساحة الاسم `xml`، داخل تعبير XPath إلى عناوين URI مناسبة للمساحات الاسمية. إذا تم تحديده كـ `null`، فإن أي بادئة مساحة اسم داخل التعبير ستؤدي إلى رمي [`DOMException`](../../../aspose.svg.dom/domexception/) مع الرمز `NAMESPACE_ERR`. |

### قيمة الإرجاع

الصيغة المجمعة لتعبير XPath.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_EXPRESSION_ERR: يُرفع إذا كان التعبير غير قانوني وفقًا لقواعد [`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | NAMESPACE_ERR: يُرفع إذا كان التعبير يحتوي على بادئات مساحات اسمية لا يمكن حلها بواسطة [`IXPathNSResolver`](../../ixpathnsresolver/) المحدد. |

### انظر أيضًا

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
