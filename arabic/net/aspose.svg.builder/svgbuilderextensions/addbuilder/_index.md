---
title: "SVGBuilderExtensions.AddBuilder"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions AddBuilder. تُضيف منشئ عنصر SVG موجود إلى منشئ عنصر SVG الحالي. تُستخدم هذه الطريقة لتضمين منشئ عنصر SVG محدد مسبقًا في المنشئ الحالي."
type: docs
weight: 60
url: /ar/net/aspose.svg.builder/svgbuilderextensions/addbuilder/
---
## SVGBuilderExtensions.AddBuilder<TBuilder,TElementBuilder> method

يضيف باني عنصر SVG موجود إلى باني عنصر SVG الحالي. تُستخدم هذه الطريقة لتضمين باني عنصر SVG مُعرّف مسبقًا في الباني الحالي.

```csharp
public static TBuilder AddBuilder<TBuilder, TElementBuilder>(this TBuilder builder, 
    TElementBuilder elementBuilder)
    where TBuilder : ISVGElementBuilder
    where TElementBuilder : ISVGElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| TElementBuilder | نوع منشئ عنصر SVG الذي سيُكوَّن. يجب أن يُنفّذ TElementBuilder الواجهة ISVGElementBuilder. |
| builder | منشئ عنصر SVG الذي يُضاف إليه منشئ العنصر الآخر. |
| elementBuilder | مُنشئ عنصر SVG الذي سيُضاف. |

### قيمة الإرجاع

مُنشئ عنصر SVG الأصلي لتسلسل الطرق.

### انظر أيضًا

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
