---
title: "SVGPatternElementBuilder فئة"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Builder.SVGPatternElementBuilder. فئة بناء لإنشاء عنصر نمط SVG يُستخدم لتعريف نمط يُستعمل لملء عناصر الرسومات داخل SVG. توفر هذه الفئة طرقًا لتعيين سمات مختلفة خاصة بعنصر النمط ولإنشاء محتواه."
type: docs
weight: 1540
url: /ar/net/aspose.svg.builder/svgpatternelementbuilder/
---
## SVGPatternElementBuilder class

فئة Builder لإنشاء عنصر SVG 'pattern'، الذي يُستخدم لتحديد نمط يُستَخدم لملء عناصر الرسومات داخل SVG. توفر هذه الفئة طرقًا لتعيين سمات مختلفة خاصة بعنصر 'pattern' وبناء محتواه.

```csharp
public class SVGPatternElementBuilder : SVGElementBuilder<SVGPatternElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, IRectAttributeSetter, 
    IViewBoxAttributeSetter
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [SVGPatternElementBuilder](svgpatternelementbuilder/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGPatternElement](../../aspose.svg/svgpatternelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgpatternelementbuilder/href/)(*string*) | يضبط سمة 'href' لعنصر SVG 'pattern'، محددًا إشارة إلى نمط آخر يرث هذا النمط سماته منه. |
| [PatternContentUnits](../../aspose.svg.builder/svgpatternelementbuilder/patterncontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | يضبط سمة 'patternContentUnits' لعنصر SVG 'pattern'، محددًا نظام الإحداثيات لمحتويات النمط. |
| [PatternTransform](../../aspose.svg.builder/svgpatternelementbuilder/patterntransform/)(*Func&lt;TransformBuilder, TransformBuilder&gt;*) | يضبط سمة 'patternTransform' لعنصر SVG 'pattern'، مطبقًا تحويلًا على النمط. |
| [PatternUnits](../../aspose.svg.builder/svgpatternelementbuilder/patternunits/)(*[CoordinateUnits](../coordinateunits/)*) | يضبط سمة 'patternUnits' لعنصر SVG 'pattern'، محددًا نظام الإحداثيات لـ x و y والعرض والارتفاع الخاص بالنمط. |

### انظر أيضًا

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGPatternElement](../../aspose.svg/svgpatternelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
