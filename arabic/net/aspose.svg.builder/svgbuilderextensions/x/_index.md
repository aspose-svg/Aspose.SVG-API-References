---
title: "SVGBuilderExtensions.X"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions X. تقوم بتعيين سمة x لعنصر SVG"
type: docs
weight: 2360
url: /ar/net/aspose.svg.builder/svgbuilderextensions/x/
---
## X<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#x_1}

يضبط خاصية 'x' لعنصر SVG.

```csharp
public static TBuilder X<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IXAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| القيمة | القيمة لسمة 'x'. |
| type | نوع قياس الطول (الافتراضي هو البكسل). |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IXAttributeSetter](../../ixattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## X<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#x}

يضبط خاصية 'x' لتحديد موضع محتوى النص على طول المحور السيني.

```csharp
public static TBuilder X<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | مُنشئ عنصر SVG. |
| type | نوع وحدة الطول للقيم. |
| القيم | قيم موضع المحور x. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

## ملاحظات

تقوم هذه الطريقة بتعيين سمة 'x'، التي تحدد موضع(ات) النص الأفقية.

### انظر أيضًا

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
