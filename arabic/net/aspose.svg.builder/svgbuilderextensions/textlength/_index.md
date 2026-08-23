---
title: "SVGBuilderExtensions.TextLength"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions TextLength. تقوم بتعيين الطول الدقيق لمحتوى النص"
type: docs
weight: 2220
url: /ar/net/aspose.svg.builder/svgbuilderextensions/textlength/
---
## SVGBuilderExtensions.TextLength<TBuilder> method

يضبط الطول الدقيق لمحتوى النص.

```csharp
public static TBuilder TextLength<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | مُنشئ عنصر SVG. |
| القيمة | طول النص. |
| type | نوع وحدة الطول للقيمة. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

## ملاحظات

تقوم هذه الطريقة بتعيين سمة 'textLength'، محددةً الطول المطلوب لمحتوى النص، وقد تتجاوز الطول الطبيعي للنص.

### انظر أيضًا

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
