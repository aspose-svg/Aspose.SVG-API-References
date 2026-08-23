---
title: "SVGBuilderExtensions.RefX"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions RefX. تقوم بتعيين سمة refX لعنصر SVG"
type: docs
weight: 1930
url: /ar/net/aspose.svg.builder/svgbuilderextensions/refx/
---
## RefX<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#refx_1}

يضبط سمة 'refX' لعنصر SVG.

```csharp
public static TBuilder RefX<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRefCoordinatesAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| القيمة | إحداثي X المرجعي. |
| type | نوع وحدة الطول (الوضع الافتراضي هو البكسل). |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRefCoordinatesAttributeSetter](../../irefcoordinatesattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RefX<TBuilder>(*this TBuilder, [HorizontalPosition](../../horizontalposition/)*) {#refx}

يضبط سمة 'refX' لعنصر SVG باستخدام موضع أفقي محدد مسبقًا.

```csharp
public static TBuilder RefX<TBuilder>(this TBuilder builder, HorizontalPosition value)
    where TBuilder : ISVGElementBuilder, IRefCoordinatesAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| القيمة | الموضع الأفقي المحدد مسبقًا. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* enum [HorizontalPosition](../../horizontalposition/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRefCoordinatesAttributeSetter](../../irefcoordinatesattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
