---
title: Interface IXPathEvaluator
second_title: Aspose.SVG لمرجع .NET API
description: Aspose.Svg.Dom.XPath.IXPathEvaluator واجهه المستخدم. يتم توفير تقييم تعبيرات XPath بواسطةIXPathEvaluator .
type: docs
weight: 1310
url: /ar/net/aspose.svg.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

يتم توفير تقييم تعبيرات XPath بواسطة`IXPathEvaluator` .

```csharp
public interface IXPathEvaluator
```

## طُرق

| اسم | وصف |
| --- | --- |
| [CreateExpression](../../aspose.svg.dom.xpath/ixpathevaluator/createexpression/)(string, IXPathNSResolver) | لتكوين تعبير XPath تم تحليله باستخدام مساحات الأسماء التي تم حلها. يعد هذا مفيدًا عندما يُعاد استخدام تعبير في أحد التطبيقات لأنه يجعل من الممكن تجميع سلسلة التعبير في نموذج داخلي أكثر كفاءة و حل جميع بادئات مساحة الاسم التي تحدث داخل التعبير. |
| [CreateNSResolver](../../aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | تتكيف مع أي عقدة DOM لتحليل مساحات الأسماء بحيث يمكن بسهولة تقييم تعبير XPath بالنسبة إلى سياق العقدة حيث ظهر داخل المستند. يعمل هذا المحول مثل طريقة DOM المستوى 3`lookupNamespaceURI` على العقد في حل مساحة الاسمURI من بادئة معينة باستخدام المعلومات الحالية المتاحة في التسلسل الهرمي للعقدة في time lookupNamespaceURI ، يتم أيضًا حل بادئة xml الضمنية بشكل صحيح. |
| [Evaluate](../../aspose.svg.dom.xpath/ixpathevaluator/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | بتقييم سلسلة تعبير XPath وإرجاع نتيجة من النوع المحدد إن أمكن. |

### أنظر أيضا

* مساحة الاسم [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* المجسم [Aspose.SVG](../../)


