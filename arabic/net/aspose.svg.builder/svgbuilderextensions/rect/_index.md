---
title: "SVGBuilderExtensions.Rect"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions Rect. تقوم بتعيين سمات x y العرض والارتفاع لعنصر SVG لتحديد مستطيل"
type: docs
weight: 1920
url: /ar/net/aspose.svg.builder/svgbuilderextensions/rect/
---
## SVGBuilderExtensions.Rect<TBuilder> method

يضبط سمات 'x' و 'y' و 'width' و 'height' لعنصر SVG لتحديد مستطيل.

```csharp
public static TBuilder Rect<TBuilder>(this TBuilder builder, double x, double y, double width, 
    double height, LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRectAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| x | الإحداثي السيني للمستطيل. |
| y | الإحداثي الصادي للمستطيل. |
| width | عرض المستطيل. |
| height | ارتفاع المستطيل. |
| type | نوع قياس الطول لجميع الأبعاد (الافتراضي هو البكسل). |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRectAttributeSetter](../../irectattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
