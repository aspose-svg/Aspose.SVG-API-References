---
title: "SVGBuilderExtensions.TextDecoration"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions TextDecoration. تُعيّن سمة text-decoration لعنصر SVG لتحديد الزخارف التي تُضاف إلى النص."
type: docs
weight: 2210
url: /ar/net/aspose.svg.builder/svgbuilderextensions/textdecoration/
---
## SVGBuilderExtensions.TextDecoration<TBuilder> method

يضبط سمة 'text-decoration' لعنصر SVG، معرفًا الزخارف التي تُضاف إلى النص.

```csharp
public static TBuilder TextDecoration<TBuilder>(this TBuilder builder, bool underline = false, 
    bool overline = false, bool lineThrough = false, bool blink = false)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| underline | يحدد ما إذا كان يجب تسطير النص. |
| overline | يحدد ما إذا كان يجب أن يحتوي النص على خط فوقه. |
| lineThrough | يحدد ما إذا كان يجب أن يكون للنص خط يمر عبره. |
| وميض | يحدد ما إذا كان يجب أن يومض النص (غير موصى به للاستخدام). |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
