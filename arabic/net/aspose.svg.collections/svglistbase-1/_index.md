---
title: "فئة SVGListBaseT"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "الفئة Aspose.Svg.Collections.SVGListBase1T. تعرف هذه الواجهة قائمة أساسية لجميع قوائم SVG."
type: docs
weight: 2040
url: /ar/net/aspose.svg.collections/svglistbase-1/
---
## SVGListBase<T> class

تعرف هذه الواجهة قائمة أساسية لجميع قوائم SVG.

```csharp
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| معامل | الوصف |
| --- | --- |
| T | نوع العنصر المخزن في القائمة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Item](../../aspose.svg.collections/svglistbase-1/item/) { get; set; } | يعيد العنصر رقم الفهرس في القائمة. |
| [Length](../../aspose.svg.collections/svglistbase-1/length/) { get; } | عدد العناصر في القائمة. |
| [NumberOfItems](../../aspose.svg.collections/svglistbase-1/numberofitems/) { get; } | عدد العناصر في القائمة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AppendItem](../../aspose.svg.collections/svglistbase-1/appenditem/)(*T*) | يدرج عنصرًا جديدًا في نهاية القائمة. |
| [Clear](../../aspose.svg.collections/svglistbase-1/clear/)() | يمسح جميع العناصر الحالية الموجودة في القائمة، بحيث تكون النتيجة قائمة فارغة. |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | يطلق الموارد غير المُدارة و- اختياريًا - المُدارة. |
| [GetEnumerator](../../aspose.svg.collections/svglistbase-1/getenumerator/)() | يحصل على المُعدِّد. |
| [GetItem](../../aspose.svg.collections/svglistbase-1/getitem/)(*ulong*) | يعيد العنصر المحدد من القائمة. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [Initialize](../../aspose.svg.collections/svglistbase-1/initialize/)(*T*) | يمسح جميع العناصر الحالية الموجودة في القائمة ويعيد تهيئة القائمة لتحتوي على العنصر الوحيد المحدد بواسطة المعامل. |
| [InsertItemBefore](../../aspose.svg.collections/svglistbase-1/insertitembefore/)(*T, ulong*) | يدرج عنصرًا جديدًا في القائمة في الموضع المحدد. العنصر الأول هو الرقم 0. |
| [RemoveItem](../../aspose.svg.collections/svglistbase-1/removeitem/)(*ulong*) | يزيل عنصرًا موجودًا من القائمة. |
| [ReplaceItem](../../aspose.svg.collections/svglistbase-1/replaceitem/)(*T, ulong*) | يستبدل عنصرًا موجودًا في القائمة بعنصر جديد. |

### انظر أيضًا

* class [SVGValueType](../../aspose.svg.datatypes/svgvaluetype/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
