---
title: "SVGListBase-1.GetItem"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة GetItem في SVGListBase. تُرجع العنصر المحدد من القائمة"
type: docs
weight: 70
url: /ar/net/aspose.svg.collections/svglistbase-1/getitem/
---
## SVGListBase<T>.GetItem method

يعيد العنصر المحدد من القائمة.

```csharp
public T GetItem(ulong index)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| index | UInt64 | فهرس العنصر من القائمة الذي سيتم إرجاعه. العنصر الأول هو الرقم 0. |

### قيمة الإرجاع

العنصر المحدد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | الرمز [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). يُرفع إذا كان رقم الفهرس أكبر من أو يساوي numberOfItems. |

### انظر أيضًا

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
