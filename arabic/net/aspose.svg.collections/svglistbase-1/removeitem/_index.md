---
title: "SVGListBase-1.RemoveItem"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة RemoveItem في SVGListBase. تُزيل عنصرًا موجودًا من القائمة"
type: docs
weight: 100
url: /ar/net/aspose.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase<T>.RemoveItem method

يزيل عنصرًا موجودًا من القائمة.

```csharp
public T RemoveItem(ulong index)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| index | UInt64 | فهرس العنصر الذي سيتم إزالته. العنصر الأول هو الرقم 0. |

### قيمة الإرجاع

العنصر المُزال.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | الرمز [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). يُرفع عندما لا يمكن تعديل القائمة. |
| [DOMException](../../../aspose.svg.dom/domexception/) | الرمز [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). يُرفع إذا كان رقم الفهرس أكبر من أو يساوي numberOfItems. |

### انظر أيضًا

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
