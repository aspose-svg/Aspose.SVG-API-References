---
title: "SVGCircleElementBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGCircleElementBuilder sınıfı. SVG içinde daireler çizmek için kullanılan bir SVG circle öğesini oluşturmak amacıyla tasarlanmış Builder sınıfı. circle öğesi içinde içerik oluşturmayı sağlar ve SVG'deki circle öğesine özgü çeşitli öznitelikleri ayarlamak için yöntemler sunar."
type: docs
weight: 1120
url: /tr/net/aspose.svg.builder/svgcircleelementbuilder/
---
## SVGCircleElementBuilder class

Builder class for constructing an SVG 'circle' element, which is used to draw circles within SVG graphics. It enables the building of content within the 'circle' element and provides methods to set various attributes specific to the 'circle' element in SVG.

```csharp
public class SVGCircleElementBuilder : SVGElementBuilder<SVGCircleElement>, 
    IAnimationElementBuilder, IDescriptiveElementBuilder, IPaintServerElementBuilder, 
    IShapeAttributeSetter, IShapeContentElementBuilder
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGCircleElementBuilder](svgcircleelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGCircleElement](../../aspose.svg/svgcircleelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Cx](../../aspose.svg.builder/svgcircleelementbuilder/cx/)(*double, [LengthType](../lengthtype/)*) | SVG 'circle' öğesinin 'cx' özniteliğini ayarlar, dairenin merkezinin x koordinatını belirtir. |
| [Cy](../../aspose.svg.builder/svgcircleelementbuilder/cy/)(*double, [LengthType](../lengthtype/)*) | SVG 'circle' öğesinin 'cy' özniteliğini ayarlar, dairenin merkezinin y koordinatını belirtir. |
| [R](../../aspose.svg.builder/svgcircleelementbuilder/r/)(*double, [LengthType](../lengthtype/)*) | SVG 'circle' öğesinin 'r' özniteliğini ayarlar, dairenin yarıçapını belirtir. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGCircleElement](../../aspose.svg/svgcircleelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IShapeAttributeSetter](../ishapeattributesetter/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
