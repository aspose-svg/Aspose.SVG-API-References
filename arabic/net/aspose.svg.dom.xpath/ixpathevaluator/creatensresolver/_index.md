---
title: "IXPathEvaluator.CreateNSResolver"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة IXPathEvaluator CreateNSResolver. تُكيّف أي عقدة DOM لحل المساحات الاسمية بحيث يمكن تقييم تعبير XPath بسهولة بالنسبة لسياق العقدة التي ظهر فيها داخل المستند. يعمل هذا المُكيّف مثل طريقة DOM Level 3 lookupNamespaceURI على العقد في حل namespaceURI من بادئة معينة باستخدام المعلومات الحالية المتوفرة في هيكلية العقدة في الوقت الذي تُستدعى فيه lookupNamespaceURI، كما يحل بشكل صحيح البادئة الضمنية xml."
type: docs
weight: 20
url: /ar/net/aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

يتكيف مع أي عقدة DOM لحل مساحات الأسماء بحيث يمكن تقييم تعبير XPath بسهولة بالنسبة لسياق العقدة التي ظهرت فيها داخل المستند. يعمل هذا المحول مثل طريقة DOM Level 3 `lookupNamespaceURI` على العقد في حل namespaceURI من بادئة معينة باستخدام المعلومات الحالية المتاحة في تسلسل العقدة الهرمي في الوقت الذي يتم فيه استدعاء lookupNamespaceURI، كما يحل بشكل صحيح البادئة الضمنية xml.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| nodeResolver | Node | العقدة التي ستُستخدم كسياق لحل المساحات الاسمية. |

### قيمة الإرجاع

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves namespaces with respect to the definitions in scope for a specified node.

### انظر أيضًا

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
