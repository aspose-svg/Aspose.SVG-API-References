---
title: "واجهة IXPathNSResolver"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "واجهة Aspose.Svg.Dom.XPath.IXPathNSResolver. تسمح واجهة XPathNSResolver بسلاسل البادئة في التعبير بأن تكون مرتبطة بشكل صحيح بسلاسل namespaceURI. يمكن لـ IXPathEvaluator إنشاء تنفيذ لـ IXPathNSResolver من عقدة أو قد يتم تنفيذ الواجهة من قبل أي تطبيق"
type: docs
weight: 3330
url: /ar/net/aspose.svg.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

تسمح واجهة `XPathNSResolver` بسلاسل `prefix` في التعبير بأن تكون مرتبطة بشكل صحيح بسلاسل `namespaceURI`. يمكن لـ [`IXPathEvaluator`](../ixpathevaluator/) إنشاء تنفيذ لـ `IXPathNSResolver` من عقدة، أو قد يتم تنفيذ الواجهة من قبل أي تطبيق.

```csharp
public interface IXPathNSResolver
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [LookupNamespaceURI](../../aspose.svg.dom.xpath/ixpathnsresolver/lookupnamespaceuri/)(*string*) | ابحث عن URI مساحة الاسم المرتبط بالبادئة المحددة. يجب ألا يستدعي مقيم XPath هذا أبداً مع قيمة `null` أو فارغة، لأن نتيجة القيام بذلك غير معرفة. |

### انظر أيضًا

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
