---
title: "فئة ImageRenderingOptions"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "الفئة Aspose.Svg.Rendering.Image.ImageRenderingOptions. تمثل خيارات العرض لـ ImageDevice. تُستخدم هذه الخيارات لتحديد تنسيق الصورة الناتج، الضغط، الدقة، إلخ."
type: docs
weight: 4940
url: /ar/net/aspose.svg.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

يمثل خيارات العرض لـ [`ImageDevice`](../imagedevice/). تُستخدم هذه الخيارات لتحديد تنسيق الصورة الناتج، الضغط، الدقة، إلخ.

```csharp
public class ImageRenderingOptions : RenderingOptions
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | يُنشئ مثيلاً جديدًا من الفئة `ImageRenderingOptions`؛ سيتم استخدام Png كتنسيق صورة افتراضي. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(*[ImageFormat](../imageformat/)*) | يُنشئ مثيلاً جديدًا من الفئة `ImageRenderingOptions` بالتنسيق الصورة المحدد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackgroundColor](../../aspose.svg.rendering/renderingoptions/backgroundcolor/) { get; set; } | يحصل أو يضبط اللون الذي سيملأ خلفية كل صفحة. القيمة الافتراضية هي شفافة. |
| [Compression](../../aspose.svg.rendering.image/imagerenderingoptions/compression/) { get; set; } | يضبط أو يحصل على ضغط تنسيق ملف الصورة الموسوم (TIFF) [`Compression`](../compression/). بشكل افتراضي، تكون هذه الخاصية LZW. |
| [Css](../../aspose.svg.rendering/renderingoptions/css/) { get; } | يحصل على كائن [`CssOptions`](../../aspose.svg.rendering/cssoptions/) يُستخدم لتكوين معالجة خصائص CSS. |
| [Format](../../aspose.svg.rendering.image/imagerenderingoptions/format/) { get; set; } | يضبط أو يحصل على [`ImageFormat`](../imageformat/). بشكل افتراضي، تكون هذه الخاصية Png. |
| override [HorizontalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | يضبط أو يحصل على الدقة الأفقية للصور الناتجة والداخلية (التي تُستخدم أثناء معالجة الفلاتر)، بوحدة البكسل لكل بوصة. القيمة الافتراضية لهذه الخاصية هي 300 نقطة في البوصة. |
| [PageSetup](../../aspose.svg.rendering/renderingoptions/pagesetup/) { get; } | يحصل على كائن إعداد الصفحة يُستخدم لتكوين مجموعة صفحات الإخراج. |
| [Text](../../aspose.svg.rendering.image/imagerenderingoptions/text/) { get; } | يحصل على كائن [`TextOptions`](../textoptions/) الذي يُستخدم لتكوين عرض النص. |
| [UseAntialiasing](../../aspose.svg.rendering.image/imagerenderingoptions/useantialiasing/) { get; set; } | يحدد ما إذا كان سيتم استخدام مضاد التسنين. بشكل افتراضي، يكون مضاد التسنين مفعلاً. |
| override [VerticalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | يضبط أو يحصل على الدقة العمودية للصور الناتجة والداخلية (التي تُستخدم أثناء معالجة الفلاتر)، بوحدة البكسل لكل بوصة. القيمة الافتراضية لهذه الخاصية هي 300 نقطة في البوصة. |

### انظر أيضًا

* class [RenderingOptions](../../aspose.svg.rendering/renderingoptions/)
* namespace [Aspose.Svg.Rendering.Image](../../aspose.svg.rendering.image/)
* assembly [Aspose.SVG](../../)
