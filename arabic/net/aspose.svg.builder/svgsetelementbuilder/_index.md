---
title: "فئة SVGSetElementBuilder"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Builder.SVGSetElementBuilder فئة. فئة بنائية لإنشاء عنصر set في SVG. يُستخدم عنصر set لتعريف رسوم متحركة بسيطة حيث يتغير قيمة سمة واحدة على مدى فترة زمنية. توفر هذه الفئة طرقًا لتعيين سمات مختلفة خاصة بعنصر set مثل السمة الهدف والقيمة المراد تعيينها."
type: docs
weight: 1610
url: /ar/net/aspose.svg.builder/svgsetelementbuilder/
---
## SVGSetElementBuilder class

فئة Builder لإنشاء عنصر SVG 'set'. يُستخدم عنصر 'set' لتعريف حركة بسيطة حيث يتغير قيمة سمة واحدة على مدى فترة زمنية. توفر هذه الفئة طرقًا لتعيين سمات مختلفة خاصة بعنصر 'set'، مثل سمة الهدف والقيمة التي سيتم تعيينها.

```csharp
public class SVGSetElementBuilder : SVGElementBuilder<SVGSetElement>, 
    IAnimationEventAttributeSetter, IAnimationTargetAttributeSetter, 
    IAnimationTargetElementAttributeSetter, IAnimationTimingAttributeSetter, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [SVGSetElementBuilder](svgsetelementbuilder/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGSetElement](../../aspose.svg/svgsetelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [To](../../aspose.svg.builder/svgsetelementbuilder/to/)(*string*) | يضبط السمة 'to' لعنصر SVG 'set'، محددًا القيمة النهائية للسمة التي سيتغير خلال الرسوم المتحركة. |

### انظر أيضًا

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGSetElement](../../aspose.svg/svgsetelement/)
* interface [IAnimationEventAttributeSetter](../ianimationeventattributesetter/)
* interface [IAnimationTargetAttributeSetter](../ianimationtargetattributesetter/)
* interface [IAnimationTargetElementAttributeSetter](../ianimationtargetelementattributesetter/)
* interface [IAnimationTimingAttributeSetter](../ianimationtimingattributesetter/)
* interface [IConditionalProcessingAttributeSetter](../iconditionalprocessingattributesetter/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
