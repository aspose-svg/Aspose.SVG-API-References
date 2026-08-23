---
title: "Document.CreateElement"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Document CreateElement. تُنشئ عنصر HTML المحدد بواسطة localName أو HTMLUnknownElement إذا لم يُعترف بـ localName."
type: docs
weight: 850
url: /ar/net/aspose.svg.dom/document/createelement/
---
## Document.CreateElement method

ينشئ عنصر HTML المحدد بـ localName، أو HTMLUnknownElement إذا لم يُعترف بـ localName.

```csharp
public Element CreateElement(string localName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| localName | String | سلسلة تحدد نوع العنصر الذي سيتم إنشاؤه. يتم تهيئة nodeName للعنصر المُنشأ بقيمة localName. لا تستخدم الأسماء المؤهلة (مثل "html:a") مع هذه الطريقة. عند استدعائها على مستند HTML، تقوم createElement() بتحويل localName إلى أحرف صغيرة قبل إنشاء العنصر. |

### قيمة الإرجاع

العنصر الجديد [`Element`](../../element/).

### انظر أيضًا

* class [Element](../../element/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
