---
title: "SVGBuilderExtensions.AddContent"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions AddContent. تضيف محتوى نصي إلى عنصر SVG"
type: docs
weight: 90
url: /ar/net/aspose.svg.builder/svgbuilderextensions/addcontent/
---
## SVGBuilderExtensions.AddContent<TBuilder> method

يضيف محتوى نصي إلى عنصر SVG.

```csharp
public static TBuilder AddContent<TBuilder>(this TBuilder builder, string text)
    where TBuilder : ISVGElementBuilder, ITextContentSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | مُنشئ عنصر SVG. |
| نص | النص الذي سيُضاف إلى العنصر. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

## ملاحظات

هذه الطريقة تسمح بإضافة محتوى نصي مباشرة إلى عنصر SVG. إنها مفيدة للعناصر التي تحتوي على بيانات نصية.

### انظر أيضًا

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentSetter](../../itextcontentsetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
