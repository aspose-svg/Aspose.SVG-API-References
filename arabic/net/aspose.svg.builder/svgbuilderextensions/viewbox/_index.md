---
title: "SVGBuilderExtensions.ViewBox"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions ViewBox. تقوم بتعيين سمة viewBox لعنصر SVG"
type: docs
weight: 2300
url: /ar/net/aspose.svg.builder/svgbuilderextensions/viewbox/
---
## SVGBuilderExtensions.ViewBox<TBuilder> method

يضبط سمة 'viewBox' لعنصر SVG.

```csharp
public static TBuilder ViewBox<TBuilder>(this TBuilder builder, double minX, double minY, 
    double width, double height)
    where TBuilder : ISVGElementBuilder, IViewBoxAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| minX | أقل إحداثي X لـ viewBox. |
| minY | أقل إحداثي Y لـ viewBox. |
| width | عرض viewBox. |
| height | ارتفاع viewBox. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IViewBoxAttributeSetter](../../iviewboxattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
