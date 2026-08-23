---
title: "Document.GetElementsByTagName"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Document GetElementsByTagName. تُعيد هذه الطريقة مجموعة HTMLCollection من العناصر التي تحمل الاسم الوسمي المحدد."
type: docs
weight: 980
url: /ar/net/aspose.svg.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

تُعيد هذه الطريقة [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) من العناصر التي تحمل الاسم الوسمي المحدد.

يتم البحث في كامل الوثيقة، بما في ذلك العقدة الجذرية. الـ [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) المرجعة هي مجموعة حية، مما يعني أنها تُحدّث نفسها تلقائيًا لتظل متزامنة مع شجرة DOM دون الحاجة لاستدعاء هذه الطريقة مرة أخرى.

```csharp
public HTMLCollection GetElementsByTagName(string tagname)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| tagname | String | سلسلة تمثل اسم العناصر. السلسلة الخاصة "*" تمثل جميع العناصر. |

### قيمة الإرجاع

مجموعة حية [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) من العناصر التي تم العثور عليها بترتيب ظهورها في الشجرة.

## ملاحظات

راجع المواصفة الرسمية [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname).

### انظر أيضًا

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
