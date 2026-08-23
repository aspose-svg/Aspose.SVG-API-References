---
title: "SVGBuilderExtensions.FloodOpacity"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions FloodOpacity. تقوم بتعيين سمة flood-opacity لعنصر SVG. يجب أن تكون القيمة بين 0.0 شفافة تمامًا و1.0 غير شفافة تمامًا"
type: docs
weight: 860
url: /ar/net/aspose.svg.builder/svgbuilderextensions/floodopacity/
---
## SVGBuilderExtensions.FloodOpacity<TBuilder> method

يضبط خاصية 'flood-opacity' لعنصر SVG. يجب أن تكون القيمة بين 0.0 (شفاف تمامًا) و 1.0 (معتم تمامًا).

```csharp
public static TBuilder FloodOpacity<TBuilder>(this TBuilder builder, double opacity)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| الشفافية | قيمة الشفافية المراد تعيينها. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | يتم إلقاؤها إذا لم تكن قيمة الشفافية ضمن النطاق الصالح. |

### انظر أيضًا

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
