---
title: "الفئة SVGImageElementBuilder"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "الفئة Aspose.Svg.Builder.SVGImageElementBuilder. فئة بناء لإنشاء عنصر صورة SVG. يُستخدم هذا العنصر لتضمين الصور داخل رسومات SVG. يوفر طرقًا لضبط خصائص مختلفة خاصة بعنصر الصورة وإضافة تكوينات إضافية مثل مسارات القص، الأقنعة، الأنماط والسكريبتات."
type: docs
weight: 1470
url: /ar/net/aspose.svg.builder/svgimageelementbuilder/
---
## SVGImageElementBuilder class

فئة Builder لإنشاء عنصر SVG 'image'. يُستخدم هذا العنصر لتضمين الصور داخل رسومات SVG. يوفر طرقًا لتعيين سمات مختلفة خاصة بعنصر 'image' وإضافة تكوينات إضافية مثل مسارات القص، الأقنعة، الأنماط، والسكربتات.

```csharp
public class SVGImageElementBuilder : SVGElementBuilder<SVGImageElement>, IAnimationElementBuilder, 
    ICompositeAttributeSetter, IDescriptiveElementBuilder, IPreserveAspectRatioAttributeSetter, 
    IRectAttributeSetter
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [SVGImageElementBuilder](svgimageelementbuilder/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddClipPath](../../aspose.svg.builder/svgimageelementbuilder/addclippath/)(*Action&lt;SVGClipPathElementBuilder&gt;*) | يضيف تكوين مسار قص إلى عنصر SVG 'image'. |
| [AddMask](../../aspose.svg.builder/svgimageelementbuilder/addmask/)(*Action&lt;SVGMaskElementBuilder&gt;*) | يضيف تكوين قناع إلى عنصر SVG 'image'. |
| [AddScript](../../aspose.svg.builder/svgimageelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | يضيف تكوين سكريبت إلى عنصر SVG 'image'. |
| [AddStyle](../../aspose.svg.builder/svgimageelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | يضيف تكوين نمط إلى عنصر SVG 'image'. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGImageElement](../../aspose.svg/svgimageelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgimageelementbuilder/href/)(*string*) | يضبط خاصية 'href' لعنصر SVG 'image'، محددًا عنوان URL للصورة التي سيتم تضمينها. |
| [HrefBase64FromBytes](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64frombytes/)(*byte[], string*) | يضبط خاصية 'href' لعنصر SVG 'image' باستخدام بايتات مشفّرة بقاعدة64 لصورة. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile)(*string*) | يضبط خاصية 'href' لعنصر SVG 'image' باستخدام ملف صورة مشفّر بقاعدة64. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile_1)(*string, string*) | يضبط خاصية 'href' لعنصر SVG 'image' باستخدام ملف صورة مشفّر بقاعدة64 مع نوع MIME محدد. |

### انظر أيضًا

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGImageElement](../../aspose.svg/svgimageelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
