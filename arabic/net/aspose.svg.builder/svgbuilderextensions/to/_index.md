---
title: "SVGBuilderExtensions.To"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions To. تُعيّن سمة to التي تحدد القيمة النهائية للرسوم المتحركة بنوع طول محدد."
type: docs
weight: 2250
url: /ar/net/aspose.svg.builder/svgbuilderextensions/to/
---
## SVGBuilderExtensions.To<TBuilder> method

يضبط سمة 'to'، معرفًا القيمة النهائية للرسوم المتحركة بنوع الطول المحدد.

```csharp
public static TBuilder To<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | مُنشئ عنصر SVG. |
| القيمة | القيمة النهائية للرسوم المتحركة. |
| type | نوع الطول لقيمة 'to'. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
