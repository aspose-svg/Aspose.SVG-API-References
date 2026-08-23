---
title: "SVGListBase-1.ReplaceItem"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة ReplaceItem في SVGListBase-1. تستبدل عنصرًا موجودًا في القائمة بعنصر جديد"
type: docs
weight: 110
url: /ar/net/aspose.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase<T>.ReplaceItem method

يستبدل عنصرًا موجودًا في القائمة بعنصر جديد.

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newItem | T | العنصر الذي سيتم إدراجه في القائمة. |
| index | UInt64 | فهرس العنصر الذي سيتم استبداله. العنصر الأول هو الرقم 0. |

### قيمة الإرجاع

العنصر المُدرج.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | الرمز [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). يُرفع عندما لا يمكن تعديل القائمة. |
| [DOMException](../../../aspose.svg.dom/domexception/) | الرمز [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). يُرفع إذا كان رقم الفهرس أكبر من أو يساوي numberOfItems. |

### انظر أيضًا

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
