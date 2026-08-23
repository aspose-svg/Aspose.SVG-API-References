---
title: "فئة SVGStyleElementBuilder"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Builder.SVGStyleElementBuilder. فئة بناء لإنشاء عنصر نمط SVG. تسهل هذه الفئة إنشاء وتكوين عنصر نمط SVG باستخدام قواعد CSS"
type: docs
weight: 1630
url: /ar/net/aspose.svg.builder/svgstyleelementbuilder/
---
## SVGStyleElementBuilder class

فئة Builder لإنشاء عنصر SVG 'style'. تُسهل هذه الفئة إنشاء وتكوين عنصر نمط SVG باستخدام قواعد CSS.

```csharp
public class SVGStyleElementBuilder : SVGElementBuilder<SVGStyleElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [SVGStyleElementBuilder](svgstyleelementbuilder/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddComment](../../aspose.svg.builder/svgstyleelementbuilder/addcomment/)(*string*) | يضيف تعليقًا إلى محتوى النمط. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule)(*string, Action&lt;RuleBuilder&gt;*) | يضيف قاعدة CSS إلى عنصر النمط باستخدام RuleBuilder. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule_1)(*string, string*) | يضيف قاعدة CSS إلى عنصر النمط. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgstyleelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | يبني عنصر نمط SVG باستخدام قواعد CSS المتراكمة ويضيفه إلى المستند المحدد. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStyleElement](../../aspose.svg/svgstyleelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Media](../../aspose.svg.builder/svgstyleelementbuilder/media/)(*string*) | يضبط السمة 'media' لعنصر SVG 'style'. تحدد هذه السمة الوسائط التي يُقصد بها الأنماط، مما يسمح بأن تكون الأنماط مشروطة بنوع الوسائط. |
| [Title](../../aspose.svg.builder/svgstyleelementbuilder/title/)(*string*) | يضبط السمة 'title' لعنصر SVG 'style'. توفر هذه السمة عنوانًا إرشاديًا لعنصر النمط، مما قد يكون مفيدًا لإمكانية الوصول ونص التلميحات. |
| [Type](../../aspose.svg.builder/svgstyleelementbuilder/type/)(*string*) | يضبط السمة 'type' لعنصر SVG 'style'. تحدد هذه السمة لغة ورقة الأنماط لمحتويات العنصر. |

### انظر أيضًا

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStyleElement](../../aspose.svg/svgstyleelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
