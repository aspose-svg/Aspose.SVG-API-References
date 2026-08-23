---
title: "Document.GetElementsByTagNameNS"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Document GetElementsByTagNameNS. تُرجع قائمة من العناصر التي لها اسم الوسم المحدد وتنتسب إلى مساحة الاسم المحددة. يتم البحث في المستند بالكامل بما في ذلك العقدة الجذرية"
type: docs
weight: 990
url: /ar/net/aspose.svg.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

تُرجع قائمة بالعناصر التي تحمل اسم الوسم المحدد وتنتمي إلى مساحة الاسم المحددة. يتم البحث في المستند بالكامل، بما في ذلك العقدة الجذرية.

```csharp
public HTMLCollection GetElementsByTagNameNS(string namespaceURI, string localName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| namespaceURI | String | معرف URI مساحة الاسم للعناصر المراد البحث عنها. |
| localName | String | إما اسم العنصر المحلي المراد البحث عنه أو القيمة الخاصة *, التي تطابق جميع العناصر. |

### قيمة الإرجاع

قائمة [`NodeList`](../../../aspose.svg.collections/nodelist/) حية للعناصر التي تم العثور عليها بالترتيب الذي تظهر به في الشجرة.

## ملاحظات

راجع المواصفة الرسمية [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens).

### انظر أيضًا

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
