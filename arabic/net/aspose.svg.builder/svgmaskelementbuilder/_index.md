---
title: "فئة SVGMaskElementBuilder"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Builder.SVGMaskElementBuilder. فئة الباني لإنشاء عنصر قناع SVG يُستخدم لتعريف قناع ألفا لتجميع الكائن الحالي في الخلفية. تمكّن هذه الفئة من بناء المحتوى داخل عنصر القناع وتوفر طرقًا لتعيين سمات مختلفة خاصة بعنصر القناع في SVG."
type: docs
weight: 1510
url: /ar/net/aspose.svg.builder/svgmaskelementbuilder/
---
## SVGMaskElementBuilder class

فئة Builder لإنشاء عنصر SVG 'mask'، الذي يُستخدم لتحديد قناع ألفا لتجميع الكائن الحالي مع الخلفية. تتيح هذه الفئة بناء المحتوى داخل عنصر 'mask' وتوفر طرقًا لتعيين سمات مختلفة خاصة بعنصر 'mask' في SVG.

```csharp
public class SVGMaskElementBuilder : SVGElementBuilder<SVGMaskElement>, ICompositeElementBuilder, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IRectAttributeSetter
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [SVGMaskElementBuilder](svgmaskelementbuilder/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMaskElement](../../aspose.svg/svgmaskelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MaskContentUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskcontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | يضبط سمة 'maskContentUnits' لعنصر SVG 'mask'، محددًا نظام الإحداثيات لمحتويات القناع. |
| [MaskUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskunits/)(*[CoordinateUnits](../coordinateunits/)*) | يضبط سمة 'maskUnits' لعنصر SVG 'mask'، محددًا نظام الإحداثيات لسمات القناع. |

### انظر أيضًا

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGMaskElement](../../aspose.svg/svgmaskelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../iconditionalprocessingattributesetter/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
