---
title: "SVGBuilderExtensions.AddMetadata"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions AddMetadata. تضيف تكوين عنصر metadata إلى الباني. يُستخدم عنصر metadata لإضافة بيانات وصفية إلى محتوى SVG."
type: docs
weight: 390
url: /ar/net/aspose.svg.builder/svgbuilderextensions/addmetadata/
---
## SVGBuilderExtensions.AddMetadata<TBuilder,TElement> method

يضيف تكوين عنصر 'metadata' إلى المُنشئ. يُستخدم عنصر 'metadata' لإضافة بيانات وصفية إلى محتوى SVG.

```csharp
public static TBuilder AddMetadata<TBuilder, TElement>(this TBuilder builder, 
    Action<SVGMetadataElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| TElement | النوع الذي يمثل عنصر 'metadata' في نموذج SVG. |
| builder | كائن المُنشئ. |
| تكوين | إجراء التكوين لعنصر 'metadata'. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* class [SVGMetadataElementBuilder](../../svgmetadataelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
