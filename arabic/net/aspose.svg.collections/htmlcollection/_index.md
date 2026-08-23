---
title: "فئة HTMLCollection"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "الفئة Aspose.Svg.Collections.HTMLCollection. تمثل HTMLCollection مجموعة عامة من Element"
type: docs
weight: 2010
url: /ar/net/aspose.svg.collections/htmlcollection/
---
## HTMLCollection class

تمثل `HTMLCollection` مجموعة عامة من [`Element`](../../aspose.svg.dom/element/).

```csharp
public abstract class HTMLCollection : DOMObject, IEnumerable<Element>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| abstract [Item](../../aspose.svg.collections/htmlcollection/item/) { get; } | يعيد العنصر رقم الفهرس في المجموعة. إذا كان الفهرس أكبر من أو يساوي عدد العقد في القائمة، فإن هذا يعيد null. |
| abstract [Length](../../aspose.svg.collections/htmlcollection/length/) { get; } | عدد العقد في القائمة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| abstract [GetEnumerator](../../aspose.svg.collections/htmlcollection/getenumerator/)() | يحصل على المُعدِّد. |
| override [GetPlatformType](../../aspose.svg.collections/htmlcollection/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [NamedItem](../../aspose.svg.collections/htmlcollection/nameditem/)(*string*) | يعيد العنصر في المجموعة الذي يطابق الاسم المحدد. |

### انظر أيضًا

* class [DOMObject](../../aspose.svg.dom/domobject/)
* class [Element](../../aspose.svg.dom/element/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
