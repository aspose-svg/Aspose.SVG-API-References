---
title: "فئة SVGRadialGradientElementBuilder"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Builder.SVGRadialGradientElementBuilder. فئة بنائية لإنشاء عنصر SVG radialGradient الذي يُستخدم لتعريف تدرج شعاعي داخل رسومات SVG. تمكّن هذه الفئة من بناء المحتوى داخل عنصر radialGradient وتوفر طرقًا لتعيين سمات مختلفة خاصة بعنصر radialGradient في SVG."
type: docs
weight: 1570
url: /ar/net/aspose.svg.builder/svgradialgradientelementbuilder/
---
## SVGRadialGradientElementBuilder class

فئة Builder لإنشاء عنصر SVG 'radialGradient'، والذي يُستخدم لتعريف تدرج شعاعي داخل رسومات SVG. تمكّن هذه الفئة من بناء المحتوى داخل عنصر 'radialGradient' وتوفر طرقًا لتعيين سمات مختلفة خاصة بعنصر 'radialGradient' في SVG.

```csharp
public class SVGRadialGradientElementBuilder : SVGElementBuilder<SVGRadialGradientElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, IGradientStopElementBuilder, 
    IPresentationAttributeSetter
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [SVGRadialGradientElementBuilder](svgradialgradientelementbuilder/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddAnimateTransform](../../aspose.svg.builder/svgradialgradientelementbuilder/addanimatetransform/)(*Action&lt;SVGAnimateTransformElementBuilder&gt;*) | يضيف تكوين تحويل متحرك إلى عنصر SVG 'radialGradient'. |
| [AddScript](../../aspose.svg.builder/svgradialgradientelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | يضيف تكوين برنامج نصي إلى عنصر SVG 'radialGradient'. |
| [AddStyle](../../aspose.svg.builder/svgradialgradientelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | يضيف تكوين نمط إلى عنصر SVG 'radialGradient'. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGRadialGradientElement](../../aspose.svg/svgradialgradientelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Cx](../../aspose.svg.builder/svgradialgradientelementbuilder/cx/)(*double, [LengthType](../lengthtype/)*) | يضبط السمة 'cx' لعنصر SVG 'radialGradient'، محددًا إحداثي x لمركز التدرج. |
| [Cy](../../aspose.svg.builder/svgradialgradientelementbuilder/cy/)(*double, [LengthType](../lengthtype/)*) | يضبط السمة 'cy' لعنصر SVG 'radialGradient'، محددًا إحداثي y لمركز التدرج. |
| [Fx](../../aspose.svg.builder/svgradialgradientelementbuilder/fx/)(*double, [LengthType](../lengthtype/)*) | يضبط السمة 'fx' لعنصر SVG 'radialGradient'، محددًا إحداثي x لنقطة التركيز في التدرج. |
| [Fy](../../aspose.svg.builder/svgradialgradientelementbuilder/fy/)(*double, [LengthType](../lengthtype/)*) | يضبط السمة 'fy' لعنصر SVG 'radialGradient'، محددًا إحداثي y لنقطة التركيز في التدرج. |
| [Href](../../aspose.svg.builder/svgradialgradientelementbuilder/href/)(*string*) | يضبط السمة 'href' لعنصر SVG 'radialGradient'، محددًا إشارة إلى تدرج آخر. |
| [R](../../aspose.svg.builder/svgradialgradientelementbuilder/r/)(*double, [LengthType](../lengthtype/)*) | يضبط السمة 'r' لعنصر SVG 'radialGradient'، محددًا نصف قطر التدرج. |

### انظر أيضًا

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGRadialGradientElement](../../aspose.svg/svgradialgradientelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IGradientStopElementBuilder](../igradientstopelementbuilder/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
