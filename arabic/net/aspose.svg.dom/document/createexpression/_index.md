---
title: "Document.CreateExpression"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Document CreateExpression. تنشئ تعبير XPath محلل مع مساحات أسماء محلولة. هذا مفيد عندما يُعاد استخدام التعبير في تطبيق لأنه يجعل من الممكن تجميع سلسلة التعبير إلى شكل داخلي أكثر كفاءة وإعادة حل جميع بادئات مساحات الأسماء التي تظهر داخل التعبير."
type: docs
weight: 890
url: /ar/net/aspose.svg.dom/document/createexpression/
---
## Document.CreateExpression method

ينشئ تعبير XPath محلل مع مساحات أسماء محلولة. هذا مفيد عندما سيتم إعادة استخدام التعبير في تطبيق لأنه يجعل من الممكن تجميع سلسلة التعبير إلى شكل داخلي أكثر كفاءة وإعادة حل جميع مسافات أسماء البادئات التي تظهر داخل التعبير.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| expression | String | سلسلة تعبير XPath التي سيتم تحليلها. |
| resolver | IXPathNSResolver | يسمح `resolver` بترجمة جميع البادئات، بما في ذلك بادئة مساحة الاسم `xml`، داخل تعبير XPath إلى عناوين URI لمساحات الأسماء المناسبة. إذا تم تحديده كـ `null`، فإن أي بادئة مساحة اسم داخل التعبير ستؤدي إلى رمي [`DOMException`](../../domexception/) مع الرمز `NAMESPACE_ERR`. |

### قيمة الإرجاع

الصيغة المجمعة لتعبير XPath.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../domexception/) | INVALID_EXPRESSION_ERR: يُرفع إذا كان التعبير غير قانوني وفقًا لقواعد [`IXPathEvaluator`](../../../aspose.svg.dom.xpath/ixpathevaluator/). |
| [DOMException](../../domexception/) | NAMESPACE_ERR: يُرفع إذا كان التعبير يحتوي على بادئات مساحات أسماء لا يمكن حلها بواسطة [`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver/) المحدد. |

### انظر أيضًا

* interface [IXPathExpression](../../../aspose.svg.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
