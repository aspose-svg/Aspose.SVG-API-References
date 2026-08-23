---
title: "SVGBuilderExtensions.OnFocusIn"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions OnFocusIn. تُعيّن سمة حدث onfocusin لمعالجة أحداث التركيز داخل العنصر"
type: docs
weight: 1450
url: /ar/net/aspose.svg.builder/svgbuilderextensions/onfocusin/
---
## SVGBuilderExtensions.OnFocusIn<TBuilder> method

يضبط سمة الحدث 'onfocusin' لمعالجة أحداث التركيز-الدخول على العنصر.

```csharp
public static TBuilder OnFocusIn<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | مُنشئ عنصر SVG. |
| القيمة | دالة JavaScript أو السكريبت التي تُنفّذ عندما يحصل العنصر على التركيز، عادةً قبل حدث 'onfocus'. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

## ملاحظات

يتم تشغيل حدث 'onfocusin' عندما يكون العنصر على وشك الحصول على التركيز. يختلف هذا الحدث عن 'onfocus' لأنه يدعم الانتشار ويمكن استخدامه لاكتشاف تغييرات التركيز على العناصر الفرعية أيضًا.

### انظر أيضًا

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
