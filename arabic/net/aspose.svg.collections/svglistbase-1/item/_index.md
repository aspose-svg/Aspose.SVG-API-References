---
title: "SVGListBase-1.Item"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "خاصية Item في SVGListBase. تُعيد العنصر رقم indexth في القائمة"
type: docs
weight: 10
url: /ar/net/aspose.svg.collections/svglistbase-1/item/
---
## SVGListBase<T> indexer

يعيد العنصر رقم الفهرس في القائمة.

```csharp
public T this[ulong index] { get; set; }
```

| معامل | الوصف |
| --- | --- |
| index | الفهرس في القائمة. |

### قيمة الإرجاع

الكائن المخزن في الموضع رقم indexth في القائمة.

### Property Value

نوع العنصر المخزن في القائمة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | الرمز [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). يُرفع عندما لا يمكن تعديل القائمة. |
| [DOMException](../../../aspose.svg.dom/domexception/) | الرمز [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). يُرفع إذا كان رقم الفهرس أكبر من أو يساوي numberOfItems. |

### انظر أيضًا

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
