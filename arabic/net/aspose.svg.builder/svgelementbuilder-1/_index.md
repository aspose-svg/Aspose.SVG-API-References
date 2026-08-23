---
title: "فئة SVGElementBuilderT"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Builder.SVGElementBuilder1T. تمثل فئة أساسية لإنشاء عناصر SVG من النوع T."
type: docs
weight: 1160
url: /ar/net/aspose.svg.builder/svgelementbuilder-1/
---
## SVGElementBuilder<T> class

يمثل فئة أساسية لبناء عناصر SVG من النوع *T*.

```csharp
public abstract class SVGElementBuilder<T> : ISVGElementBuilder
    where T : SVGElement
```

| معامل | الوصف |
| --- | --- |
| T | نوع عنصر SVG الذي يتحمل هذا المنشئ مسؤولية إنشائه. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } | يحصل على قائمة التكوينات التي ستُطبق على عنصر SVG. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) | يضيف تكوين سمة إلى عنصر SVG. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | يبني عنصر SVG ويطبق جميع التكوينات عليه. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build_1)(*T*) | يطبق التكوينات على عنصر SVG موجود. |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) | يبني عنصر SVG كعنصر SVGElement عام. |

### انظر أيضًا

* interface [ISVGElementBuilder](../isvgelementbuilder/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
