---
title: "SVGBuilderExtensions.OnWaiting"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "SVGBuilderExtensions OnWaiting method. تُعيّن سمة حدث onwaiting لمعالجة الأحداث عندما يتأخر تشغيل الوسائط بسبب تخزين البيانات في الذاكرة المؤقتة."
type: docs
weight: 1850
url: /ar/net/aspose.svg.builder/svgbuilderextensions/onwaiting/
---
## SVGBuilderExtensions.OnWaiting<TBuilder> method

يضبط سمة حدث 'onwaiting' لمعالجة الأحداث عندما يتأخر تشغيل الوسائط بسبب تخزين البيانات مؤقتًا.

```csharp
public static TBuilder OnWaiting<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | مُنشئ عنصر SVG. |
| القيمة | دالة جافا سكريبت أو البرنامج النصي الذي يتم تنفيذه عندما يتأخر تشغيل الوسائط بسبب التخزين المؤقت. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
