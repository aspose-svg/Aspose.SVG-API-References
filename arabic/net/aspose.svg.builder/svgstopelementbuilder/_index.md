---
title: "فئة SVGStopElementBuilder"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Builder.SVGStopElementBuilder فئة. فئة الباني لإنشاء عنصر إيقاف SVG. يُستخدم عنصر الإيقاف داخل تعريف تدرج إما خطي أو قطري لتحديد نقاط التوقف اللونية. توفر هذه الفئة طرقًا لضبط سمات مختلفة خاصة بعنصر الإيقاف مثل الإزاحة واللون."
type: docs
weight: 1620
url: /ar/net/aspose.svg.builder/svgstopelementbuilder/
---
## SVGStopElementBuilder class

فئة Builder لإنشاء عنصر SVG 'stop'. يُستخدم عنصر 'stop' داخل تعريف التدرج (خطّي أو شعاعي) لتحديد نقاط التوقف اللونية. توفر هذه الفئة طرقًا لتعيين سمات مختلفة خاصة بعنصر 'stop'، مثل الإزاحة واللون.

```csharp
public class SVGStopElementBuilder : SVGElementBuilder<SVGStopElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [SVGStopElementBuilder](svgstopelementbuilder/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgstopelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | يضيف تكوين برنامج نصي إلى عنصر SVG 'stop'. |
| [AddStyle](../../aspose.svg.builder/svgstopelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | يضيف تكوين نمط إلى عنصر SVG 'stop'. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStopElement](../../aspose.svg/svgstopelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Offset](../../aspose.svg.builder/svgstopelementbuilder/offset/)(*double, [StopUnitType](../stopunittype/)*) | يضبط السمة 'offset' لعنصر SVG 'stop'، محددًا موضع نقطة التوقف اللونية داخل التدرج. |

### انظر أيضًا

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStopElement](../../aspose.svg/svgstopelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
