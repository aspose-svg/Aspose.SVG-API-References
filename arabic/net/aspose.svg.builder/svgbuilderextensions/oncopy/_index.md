---
title: "SVGBuilderExtensions.OnCopy"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions OnCopy. يحدد سمة الحدث oncopy التي تعرف برنامجًا نصيًا للتنفيذ عندما يتم نسخ المحتوى من عنصر SVG."
type: docs
weight: 1270
url: /ar/net/aspose.svg.builder/svgbuilderextensions/oncopy/
---
## SVGBuilderExtensions.OnCopy<TBuilder> method

يضبط سمة الحدث 'oncopy'، معرفًا برنامجًا نصيًا يُنفّذ عندما يُنسخ المحتوى من عنصر SVG.

```csharp
public static TBuilder OnCopy<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | مُنشئ عنصر SVG. |
| القيمة | دالة JavaScript أو البرنامج النصي للتنفيذ عند حدث النسخ. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
