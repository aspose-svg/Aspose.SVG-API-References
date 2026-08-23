---
title: "SVGTextElementBuilder فئة"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Builder.SVGTextElementBuilder فئة. فئة Builder لإنشاء SVGTextElement الذي يُستخدم لتعريف النص في مستند SVG."
type: docs
weight: 1670
url: /ar/net/aspose.svg.builder/svgtextelementbuilder/
---
## SVGTextElementBuilder class

فئة Builder لإنشاء SVGTextElement، والذي يُستخدم لتعريف النص في مستند SVG.

```csharp
public class SVGTextElementBuilder : SVGElementBuilder<SVGTextElement>, IAnimationElementBuilder, 
    ICompositeAttributeSetter, IDescriptiveElementBuilder, IPaintServerElementBuilder, 
    IShapeContentElementBuilder, ITextContentPositioningAttributeSetter
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [SVGTextElementBuilder](svgtextelementbuilder/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddA](../../aspose.svg.builder/svgtextelementbuilder/adda/)(*Action&lt;SVGAElementBuilder&gt;*) | يضيف عنصر 'a' (مرساة) إلى عنصر النص، مما يتيح ربط أجزاء النص عبر روابط. |
| [AddTextPath](../../aspose.svg.builder/svgtextelementbuilder/addtextpath/)(*Action&lt;SVGTextPathElementBuilder&gt;*) | يضيف عنصر 'textPath' إلى عنصر النص، مما يسمح للنص باتباع مسار محدد. |
| [AddTSpan](../../aspose.svg.builder/svgtextelementbuilder/addtspan/)(*Action&lt;SVGTSpanElementBuilder&gt;*) | يضيف عنصر 'tspan' إلى عنصر النص، مما يتيح تحكمًا دقيقًا في الأقسام الفردية للنص. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGTextElement](../../aspose.svg/svgtextelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |

### انظر أيضًا

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGTextElement](../../aspose.svg/svgtextelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../itextcontentpositioningattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
