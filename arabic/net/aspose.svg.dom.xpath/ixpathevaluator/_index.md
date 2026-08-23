---
title: "واجهة IXPathEvaluator"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "واجهة Aspose.Svg.Dom.XPath.IXPathEvaluator. يتم توفير تقييم تعبيرات XPath بواسطة IXPathEvaluator"
type: docs
weight: 3310
url: /ar/net/aspose.svg.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

يتم توفير تقييم تعبيرات XPath بواسطة `IXPathEvaluator`.

```csharp
public interface IXPathEvaluator
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreateExpression](../../aspose.svg.dom.xpath/ixpathevaluator/createexpression/)(*string, [IXPathNSResolver](../ixpathnsresolver/)*) | ينشئ تعبير XPath محلل مع مساحات أسماء محلولة. هذا مفيد عندما سيتم إعادة استخدام التعبير في تطبيق لأنه يجعل من الممكن تجميع سلسلة التعبير إلى شكل داخلي أكثر كفاءة وإعادة حل جميع مسافات أسماء البادئات التي تظهر داخل التعبير. |
| [CreateNSResolver](../../aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/)(*[Node](../../aspose.svg.dom/node/)*) | يتكيف مع أي عقدة DOM لحل مساحات الأسماء بحيث يمكن تقييم تعبير XPath بسهولة بالنسبة لسياق العقدة التي ظهرت فيها داخل المستند. يعمل هذا المحول مثل طريقة DOM Level 3 `lookupNamespaceURI` على العقد في حل namespaceURI من بادئة معينة باستخدام المعلومات الحالية المتاحة في تسلسل العقدة الهرمي في الوقت الذي يتم فيه استدعاء lookupNamespaceURI، كما يحل بشكل صحيح البادئة الضمنية xml. |
| [Evaluate](../../aspose.svg.dom.xpath/ixpathevaluator/evaluate/)(*string, [Node](../../aspose.svg.dom/node/), [IXPathNSResolver](../ixpathnsresolver/), [XPathResultType](../xpathresulttype/), object*) | يقيم سلسلة تعبير XPath ويعيد نتيجة من النوع المحدد إذا كان ذلك ممكنًا. |

### انظر أيضًا

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
