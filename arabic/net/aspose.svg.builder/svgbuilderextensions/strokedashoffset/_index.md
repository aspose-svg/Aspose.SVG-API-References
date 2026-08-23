---
title: "SVGBuilderExtensions.StrokeDashoffset"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions StrokeDashoffset. تُعيّن خاصية stroke-dashoffset لعنصر SVG لتحديد الإزاحة لبداية مصفوفة الشرط المتقطّع."
type: docs
weight: 2100
url: /ar/net/aspose.svg.builder/svgbuilderextensions/strokedashoffset/
---
## SVGBuilderExtensions.StrokeDashoffset<TBuilder> method

يضبط خاصية 'stroke-dashoffset' لعنصر SVG، محددًا الإزاحة لبداية مصفوفة شرطات الحد.

```csharp
public static TBuilder StrokeDashoffset<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| القيمة | قيمة إزاحة الشرط المتقطّع. |
| type | نوع الوحدة لقيمة الإزاحة. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
