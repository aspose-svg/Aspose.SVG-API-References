---
title: "SVGBuilderExtensions.OnSuspend"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions OnSuspend. تُعيّن سمة حدث onsuspend لمعالجة الأحداث عندما يتم إيقاف تحميل بيانات الوسائط."
type: docs
weight: 1800
url: /ar/net/aspose.svg.builder/svgbuilderextensions/onsuspend/
---
## SVGBuilderExtensions.OnSuspend<TBuilder> method

يضبط سمة حدث 'onsuspend' لمعالجة الأحداث عندما يتم إيقاف تحميل بيانات الوسائط.

```csharp
public static TBuilder OnSuspend<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | مُنشئ عنصر SVG. |
| القيمة | دالة JavaScript أو البرنامج النصي للتنفيذ عندما يتم إيقاف تحميل بيانات الوسائط. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
