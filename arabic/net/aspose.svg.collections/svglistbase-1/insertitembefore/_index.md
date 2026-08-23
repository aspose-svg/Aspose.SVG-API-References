---
title: "SVGListBase-1.InsertItemBefore"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة InsertItemBefore في SVGListBase. تُدرج عنصرًا جديدًا في القائمة في الموضع المحدد. العنصر الأول هو الرقم 0"
type: docs
weight: 90
url: /ar/net/aspose.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase<T>.InsertItemBefore method

يدرج عنصرًا جديدًا في القائمة في الموضع المحدد. العنصر الأول هو الرقم 0.

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newItem | T | العنصر الذي سيتم إدراجه في القائمة. |
| index | UInt64 | فهرس العنصر الذي سيُدرج قبلّه العنصر الجديد. العنصر الأول هو الرقم 0. إذا كان الفهرس يساوي 0، يتم إدراج العنصر الجديد في مقدمة القائمة. إذا كان الفهرس أكبر من أو يساوي numberOfItems، يتم إلحاق العنصر الجديد بنهاية القائمة. |

### قيمة الإرجاع

العنصر المُدرج.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | الرمز [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). يُرفع عندما لا يمكن تعديل القائمة. |

### انظر أيضًا

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
