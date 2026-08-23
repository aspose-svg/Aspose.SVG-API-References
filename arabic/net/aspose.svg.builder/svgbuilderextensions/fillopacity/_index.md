---
title: "SVGBuilderExtensions.FillOpacity"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions FillOpacity. تُعيّن سمة fill-opacity لعنصر SVG. يجب أن تكون القيمة بين 0.0 شفافة تمامًا و1.0 معتمة تمامًا"
type: docs
weight: 820
url: /ar/net/aspose.svg.builder/svgbuilderextensions/fillopacity/
---
## SVGBuilderExtensions.FillOpacity<TBuilder> method

يضبط خاصية 'fill-opacity' لعنصر SVG. يجب أن تكون القيمة بين 0.0 (شفاف تمامًا) و 1.0 (معتم تمامًا).

```csharp
public static TBuilder FillOpacity<TBuilder>(this TBuilder builder, double opacity)
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
