---
title: "SVGBuilderExtensions.Rotate"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions Rotate. تُعيّن زوايا الدوران للأحرف الفردية أو أقسام محتوى النص."
type: docs
weight: 2000
url: /ar/net/aspose.svg.builder/svgbuilderextensions/rotate/
---
## Rotate<TBuilder>(*this TBuilder, params double[]*) {#rotate_1}

يضبط زوايا دوران للأحرف أو القطاعات الفردية من محتوى النص.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | مُنشئ عنصر SVG. |
| القيم | مصفوفة من زوايا الدوران بالدرجات. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

## ملاحظات

تقوم هذه الطريقة بتعيين سمة 'rotate' بقيم متعددة، مما يسمح بتدوير فردي لكل حرف أو مقطع نصي.

### انظر أيضًا

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Rotate<TBuilder>(*this TBuilder, double*) {#rotate}

يضبط زاوية دوران واحدة لكامل محتوى النص.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, double value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | مُنشئ عنصر SVG. |
| القيمة | زاوية الدوران بالدرجات. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

## ملاحظات

تقوم هذه الطريقة بتعيين سمة 'rotate' بقيمة واحدة، وتطبيق نفس زاوية الدوران على جميع محتوى النص.

### انظر أيضًا

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
