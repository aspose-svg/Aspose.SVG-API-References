---
title: "Document.GetElementsByClassName"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Document GetElementsByClassName. تُعيد هذه الطريقة كائنًا شبيهًا بالمصفوفة يحتوي على جميع العناصر الفرعية التي تمتلك جميع أسماء الفئات المحددة."
type: docs
weight: 970
url: /ar/net/aspose.svg.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

تُعيد هذه الطريقة كائنًا شبيهًا بالمصفوفة يحتوي على جميع العناصر الفرعية التي لديها جميع أسماء الفئات المحددة.

عند استدعائه على كائن المستند، يتم البحث في المستند بالكامل، بما في ذلك العقدة الجذرية. يمكنك أيضًا استدعاء هذه الطريقة على أي عنصر؛ ستعيد فقط العناصر التي هي من سلالة العنصر الجذري المحدد مع اسم (أسماء) الفئة المعطاة.

```csharp
public HTMLCollection GetElementsByClassName(string classNames)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| classNames | String | السلسلة التي تحتوي على مجموعة غير مرتبة من الرموز الفريدة المفصولة بمسافات تمثل الفئات (أسماء الفئات) |

### قيمة الإرجاع

مجموعة حية [`HTMLCollection`](../../../aspose.svg.collections/htmlcollection/) من العناصر التي تم العثور عليها.

## ملاحظات

راجع المواصفة الرسمية [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname).

### انظر أيضًا

* class [HTMLCollection](../../../aspose.svg.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
