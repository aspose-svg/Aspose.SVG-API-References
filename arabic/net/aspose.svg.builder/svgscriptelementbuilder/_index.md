---
title: "فئة SVGScriptElementBuilder"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Builder.SVGScriptElementBuilder. فئة بناء لإنشاء عنصر سكريبت SVG. يُستخدم عنصر السكريبت لتضمين أو الإشارة إلى سكريبتات قابلة للتنفيذ داخل مستندات SVG. توفر هذه الفئة طرقًا لضبط سمات مختلفة خاصة بعنصر السكريبت مثل النوع والمصدر وإعدادات المصدر المتقاطع."
type: docs
weight: 1600
url: /ar/net/aspose.svg.builder/svgscriptelementbuilder/
---
## SVGScriptElementBuilder class

فئة Builder لإنشاء عنصر SVG 'script'. يُستخدم عنصر 'script' لتضمين أو الإشارة إلى سكريبتات قابلة للتنفيذ داخل مستندات SVG. توفر هذه الفئة طرقًا لتعيين سمات مختلفة خاصة بعنصر 'script'، مثل النوع والمصدر وإعدادات المصدر المتقاطع.

```csharp
public class SVGScriptElementBuilder : SVGElementBuilder<SVGScriptElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [SVGScriptElementBuilder](svgscriptelementbuilder/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGScriptElement](../../aspose.svg/svgscriptelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Crossorigin](../../aspose.svg.builder/svgscriptelementbuilder/crossorigin/)(*string*) | يضبط سمة 'crossorigin' لعنصر SVG 'script'، محددًا إعدادات CORS للسكريبت الخارجي. |
| [Href](../../aspose.svg.builder/svgscriptelementbuilder/href/)(*string*) | يضبط سمة 'href' لعنصر SVG 'script'، محددًا عنوان URL لملف سكريبت خارجي. |
| [Type](../../aspose.svg.builder/svgscriptelementbuilder/type/)(*string*) | يضبط سمة 'type' لعنصر SVG 'script'، محددًا نوع لغة البرمجة للسكريبت (مثال: "text/javascript"). |

### انظر أيضًا

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGScriptElement](../../aspose.svg/svgscriptelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
