---
title: "Node.TextContent"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "خاصية Node TextContent. تمثل محتوى النص للعقدة وتوابعها"
type: docs
weight: 160
url: /ar/net/aspose.svg.dom/node/textcontent/
---
## Node.TextContent property

يمثل محتوى النص للعقدة وتفرعاتها.

```csharp
public virtual string TextContent { get; set; }
```

### Property Value

سلسلة نصية، أو null. قيمتها تعتمد على الحالة:

إذا كانت العقدة مستندًا أو doctype، فإن `TextContent` تُعيد null. ملاحظة: للحصول على كل النص وبيانات CDATA للمستند بالكامل، استخدم

```csharp
document.DocumentElement.TextContent
```

.إذا كانت العقدة قسم CDATA أو تعليق أو تعليم معالجة أو عقدة نصية، فإن `TextContent` تُعيد أو تُعيّن النص داخل العقدة، أي [`NodeValue`](../nodevalue/). بالنسبة لأنواع العقد الأخرى، فإن `TextContent` تُعيد دمج `TextContent` لكل عقدة فرعية، مستثنية التعليقات وتعليمات المعالجة.

## ملاحظات

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-textcontent).

### انظر أيضًا

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
