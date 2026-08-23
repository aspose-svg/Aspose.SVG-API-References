---
title: "SVGBuilderExtensions.Dx"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions Dx. تقوم بتعيين السمة dx لضبط الموضع الأفقي لكل حرف في النص"
type: docs
weight: 770
url: /ar/net/aspose.svg.builder/svgbuilderextensions/dx/
---
## Dx<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#dx}

يضبط خاصية 'dx' لتعديل الموضع الأفقي لكل حرف في النص.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | مُنشئ عنصر SVG. |
| type | نوع وحدة الطول للقيم. |
| القيم | قِيَم الضبط الأفقي لكل حرف. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

## ملاحظات

تتيح هذه الطريقة تحكمًا دقيقًا في التباعد الأفقي للأحرف في النص.

### انظر أيضًا

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dx<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dx_1}

يضبط قيمة تعديل أفقية واحدة لمحتوى النص.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | مُنشئ عنصر SVG. |
| القيمة | قيمة الضبط الأفقي. |
| type | نوع وحدة الطول للقيمة. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

## ملاحظات

تقوم هذه الطريقة بتعيين السمة 'dx' بقيمة واحدة، مما يضبط الموضع الأفقي لمحتوى النص.

### انظر أيضًا

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
