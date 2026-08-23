---
title: "SVGBuilderExtensions.OnFocusOut"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions OnFocusOut. تعيين سمة الحدث onfocusout لمعالجة أحداث فقدان التركيز على العنصر"
type: docs
weight: 1460
url: /ar/net/aspose.svg.builder/svgbuilderextensions/onfocusout/
---
## SVGBuilderExtensions.OnFocusOut<TBuilder> method

يضبط سمة الحدث 'onfocusout' لمعالجة أحداث التركيز-الخروج على العنصر.

```csharp
public static TBuilder OnFocusOut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | مُنشئ عنصر SVG. |
| القيمة | دالة JavaScript أو البرنامج النصي للتنفيذ عندما يفقد العنصر التركيز، عادةً قبل حدث 'onblur'. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

## ملاحظات

يتم تشغيل حدث 'onfocusout' عندما يكون العنصر على وشك فقدان التركيز. مشابه لـ 'onfocusin'، يدعم هذا الحدث الانتشار ويمكن استخدامه لاكتشاف تغييرات التركيز على العناصر الفرعية أيضًا.

### انظر أيضًا

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
