---
title: "SVGBuilderExtensions.FontKerning"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions FontKerning. تقوم بتعيين السمة font-kerning لعنصر SVG باستخدام قيمة رقمية ونوع الطول المحدد."
type: docs
weight: 880
url: /ar/net/aspose.svg.builder/svgbuilderextensions/fontkerning/
---
## FontKerning<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#fontkerning_1}

يضبط خاصية 'font-kerning' لعنصر SVG باستخدام قيمة رقمية ونوع طول محدد.

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| القيمة | قيمة تباعد الخط التي سيتم تعيينها. |
| type | نوع الطول (مثل px, em). |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## FontKerning<TBuilder>(*this TBuilder, [Kerning](../../kerning/)*) {#fontkerning}

يضبط خاصية 'font-kerning' لعنصر SVG باستخدام قيمة تباعد حروف مسبقة التعريف.

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, Kerning value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| القيمة | قيمة التباعد المحددة مسبقًا التي سيتم تعيينها. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* enum [Kerning](../../kerning/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
