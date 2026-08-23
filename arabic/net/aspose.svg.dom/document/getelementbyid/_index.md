---
title: "Document.GetElementById"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Document GetElementById. تُرجع هذه الطريقة كائن Element يمثل العنصر الذي تتطابق خاصية id الخاصة به مع السلسلة المحددة. بما أن معرفات العناصر يجب أن تكون فريدة إذا تم تحديدها، فهي طريقة مفيدة للوصول بسرعة إلى عنصر محدد"
type: docs
weight: 960
url: /ar/net/aspose.svg.dom/document/getelementbyid/
---
## Document.GetElementById method

تُرجع هذه الطريقة كائن [`Element`](../../element/) يمثل العنصر الذي تتطابق خاصية id الخاصة به مع السلسلة المحددة. بما أن معرفات العناصر يجب أن تكون فريدة إذا تم تحديدها، فهي طريقة مفيدة للوصول بسرعة إلى عنصر محدد.

إذا كنت بحاجة للوصول إلى عنصر لا يمتلك معرفًا، يمكنك استخدام [`QuerySelector`](../queryselector/) للعثور على العنصر باستخدام أي محدد.

```csharp
public Element GetElementById(string elementId)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| elementId | String | معرف العنصر المراد تحديده. المعرف هو سلسلة حساسة لحالة الأحرف وتكون فريدة داخل المستند؛ لا يمكن أن يكون هناك أكثر من عنصر يحمل نفس المعرف. |

### قيمة الإرجاع

كائن [`Element`](../../element/) يصف كائن عنصر DOM المتطابق مع المعرف المحدد، أو null إذا لم يُعثر على عنصر متطابق في المستند.

## ملاحظات

راجع المواصفة الرسمية [spec](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid).

### انظر أيضًا

* class [Element](../../element/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
