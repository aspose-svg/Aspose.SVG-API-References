---
title: "SVGBuilderExtensions.Mask"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "SVGBuilderExtensions Mask method. تُعيّن سمة mask لعنصر SVG باستخدام تكوين mask مخصص."
type: docs
weight: 1150
url: /ar/net/aspose.svg.builder/svgbuilderextensions/mask/
---
## SVGBuilderExtensions.Mask<TBuilder> method

يضبط السمة 'mask' لعنصر SVG باستخدام تكوين قناع مخصص.

```csharp
public static TBuilder Mask<TBuilder>(this TBuilder builder, Action<MaskBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| تكوين | A delegate to configure the mask. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* class [MaskBuilder](../../maskbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
