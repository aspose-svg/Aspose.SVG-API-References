---
title: "SVGBuilderExtensions.Dy"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions Dy. تُعيّن قيم تعديل عمودية متعددة لمحتوى النص"
type: docs
weight: 780
url: /ar/net/aspose.svg.builder/svgbuilderextensions/dy/
---
## Dy<TBuilder>(*this TBuilder, double[], [LengthType](../../lengthtype/)*) {#dy_1}

يضبط قيم تعديل رأسية متعددة لمحتوى النص.

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double[] values, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | مُنشئ عنصر SVG. |
| القيم | مصفوفة قيم التعديل العمودي. |
| type | نوع وحدة الطول للقيم. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

## ملاحظات

تقوم هذه الطريقة بتعيين السمة 'dy' بقيم متعددة، مما يسمح بتعديلات عمودية فردية لكل حرف أو مقطع نصي.

### انظر أيضًا

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dy<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dy}

يضبط قيمة تعديل رأسية واحدة لمحتوى النص.

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | مُنشئ عنصر SVG. |
| القيمة | قيمة التعديل العمودي. |
| type | نوع وحدة الطول للقيمة. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

## ملاحظات

تقوم هذه الطريقة بتعيين السمة 'dy' بقيمة واحدة، تعديل الموضع العمودي لمحتوى النص.

### انظر أيضًا

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
