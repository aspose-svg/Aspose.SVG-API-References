---
title: "فئة SVGClipPathElementBuilder"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Builder.SVGClipPathElementBuilder. فئة بنائية لإنشاء عنصر SVG clipPath يُستخدم لتعريف مسار القص. تتيح بناء المحتوى داخل عنصر clipPath وتوفر طرقًا لتعيين سمات مختلفة خاصة بعنصر clipPath في SVG"
type: docs
weight: 1130
url: /ar/net/aspose.svg.builder/svgclippathelementbuilder/
---
## SVGClipPathElementBuilder class

فئة Builder لإنشاء عنصر SVG 'clipPath'، والذي يُستخدم لتعريف مسار القص. تمكّن من بناء المحتوى داخل عنصر 'clipPath' وتوفر طرقًا لتعيين سمات مختلفة خاصة بعنصر 'clipPath' في SVG.

```csharp
public class SVGClipPathElementBuilder : SVGElementBuilder<SVGClipPathElement>, 
    IAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IShapeElementBuilder
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [SVGClipPathElementBuilder](svgclippathelementbuilder/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgclippathelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | يضيف عنصر script إلى عنصر clipPath. |
| [AddText](../../aspose.svg.builder/svgclippathelementbuilder/addtext/)(*Action&lt;SVGTextElementBuilder&gt;*) | يضيف عنصر نص إلى عنصر clipPath. |
| [AddUse](../../aspose.svg.builder/svgclippathelementbuilder/adduse/)(*Action&lt;SVGUseElementBuilder&gt;*) | يضيف عنصر 'use' إلى عنصر clipPath. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGClipPathElement](../../aspose.svg/svgclippathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [ClipPathUnits](../../aspose.svg.builder/svgclippathelementbuilder/clippathunits/)(*[CoordinateUnits](../coordinateunits/)*) | يضبط سمة 'clipPathUnits' لعنصر SVG 'clipPath'، محدداً نظام الإحداثيات لمسار القص. |

### انظر أيضًا

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGClipPathElement](../../aspose.svg/svgclippathelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IShapeElementBuilder](../ishapeelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
