---
title: "فئة SVGMarkerElementBuilder"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Builder.SVGMarkerElementBuilder class. فئة بنّاءة لإنشاء عنصر SVG marker يُستخدم لتعريف العلامات الرسومية مثل رؤوس السهام أو النقاط التي يمكن إرفاقها بعناصر المسار والخط المتعدد والنقوش. تتيح هذه الفئة بناء المحتوى داخل عنصر marker وتوفر طرقًا لتعيين سمات مختلفة خاصة بعنصر marker في SVG."
type: docs
weight: 1500
url: /ar/net/aspose.svg.builder/svgmarkerelementbuilder/
---
## SVGMarkerElementBuilder class

فئة Builder لإنشاء عنصر SVG 'marker'، الذي يُستخدم لتحديد علامات رسومية، مثل رؤوس الأسهم أو النقاط، التي يمكن ربطها بعناصر 'path' و 'line' و 'polyline' و 'polygon'. تتيح هذه الفئة بناء المحتوى داخل عنصر 'marker' وتوفر طرقًا لتعيين سمات مختلفة خاصة بعنصر 'marker' في SVG.

```csharp
public class SVGMarkerElementBuilder : SVGElementBuilder<SVGMarkerElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, 
    IRefCoordinatesAttributeSetter, IViewBoxAttributeSetter
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [SVGMarkerElementBuilder](svgmarkerelementbuilder/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMarkerElement](../../aspose.svg/svgmarkerelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MarkerHeight](../../aspose.svg.builder/svgmarkerelementbuilder/markerheight/)(*double, [LengthType](../lengthtype/)*) | يضبط السمة 'markerHeight' لعنصر SVG 'marker'، محددًا ارتفاع نافذة العرض للعلامة. |
| [MarkerUnits](../../aspose.svg.builder/svgmarkerelementbuilder/markerunits/)(*[MarkerUnits](../markerunits/)*) | يضبط السمة 'markerUnits' لعنصر SVG 'marker'، محددًا نظام الإحداثيات لسمات العلامة. |
| [MarkerWidth](../../aspose.svg.builder/svgmarkerelementbuilder/markerwidth/)(*double, [LengthType](../lengthtype/)*) | يضبط السمة 'markerWidth' لعنصر SVG 'marker'، محددًا عرض نافذة العرض للعلامة. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient)(*[Orient](../orient/)*) | يضبط السمة 'orient' لعنصر SVG 'marker'، محددًا توجيه العلامة. |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient_1)(*double, [AngleUnits](../angleunits/)*) | يضبط السمة 'orient' لعنصر SVG 'marker'، محددًا زاوية توجيه العلامة. |

### انظر أيضًا

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGMarkerElement](../../aspose.svg/svgmarkerelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRefCoordinatesAttributeSetter](../irefcoordinatesattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
