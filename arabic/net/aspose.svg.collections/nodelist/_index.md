---
title: "فئة NodeList"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "الفئة Aspose.Svg.Collections.NodeList. توفر NodeList تجريدًا لمجموعة مرتبة من العقد دون تحديد أو تقييد كيفية تنفيذ هذه المجموعة."
type: docs
weight: 2030
url: /ar/net/aspose.svg.collections/nodelist/
---
## NodeList class

توفر NodeList تجريدًا لمجموعة مرتبة من العقد، دون تعريف أو تقييد كيفية تنفيذ هذه المجموعة.

```csharp
public abstract class NodeList : DOMObject, IEnumerable<Node>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| abstract [Item](../../aspose.svg.collections/nodelist/item/) { get; } | تُعيد الطريقة العنصر رقم الفهرس في المجموعة. إذا كان الفهرس أكبر من أو يساوي عدد العقد في القائمة، فإن هذا يعيد null. |
| abstract [Length](../../aspose.svg.collections/nodelist/length/) { get; } | عدد العقد في القائمة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| abstract [GetEnumerator](../../aspose.svg.collections/nodelist/getenumerator/)() | يرجع كائن enumerator يتنقل عبر المجموعة. |
| override [GetPlatformType](../../aspose.svg.collections/nodelist/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |

### انظر أيضًا

* class [DOMObject](../../aspose.svg.dom/domobject/)
* class [Node](../../aspose.svg.dom/node/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
