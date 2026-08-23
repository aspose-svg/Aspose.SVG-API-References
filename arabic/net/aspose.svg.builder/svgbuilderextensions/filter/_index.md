---
title: "SVGBuilderExtensions.Filter"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions Filter. تُعيّن سمة filter لعنصر SVG باستخدام تكوين مخصص."
type: docs
weight: 840
url: /ar/net/aspose.svg.builder/svgbuilderextensions/filter/
---
## SVGBuilderExtensions.Filter<TBuilder> method

يضبط خاصية 'filter' لعنصر SVG باستخدام تكوين مخصص.

```csharp
public static TBuilder Filter<TBuilder>(this TBuilder builder, 
    Action<FilterValueListBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| تكوين | مُفَوَّض لتكوين FilterValueListBuilder. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* class [FilterValueListBuilder](../../filtervaluelistbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
