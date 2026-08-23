---
title: "SVGBuilderExtensions.OnAbort"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions OnAbort. تقوم بتعيين سمة حدث onabort التي تحدد سكريبتًا لتشغيله عندما يتم إلغاء تحميل مستند SVG."
type: docs
weight: 1190
url: /ar/net/aspose.svg.builder/svgbuilderextensions/onabort/
---
## SVGBuilderExtensions.OnAbort<TBuilder> method

يضبط سمة الحدث 'onabort'، معرفًا برنامجًا نصيًا يُنفّذ عندما يُلغى تحميل مستند SVG.

```csharp
public static TBuilder OnAbort<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentEventAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | مُنشئ عنصر SVG. |
| القيمة | دالة JavaScript أو السكريبت الذي يُنفّذ عندما يتم إلغاء تحميل المستند. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentEventAttributeSetter](../../idocumenteventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
