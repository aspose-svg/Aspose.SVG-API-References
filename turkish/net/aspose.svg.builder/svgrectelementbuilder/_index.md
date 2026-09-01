---
title: "SVGRectElementBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGRectElementBuilder sınıf. SVG rect öğesini oluşturmak için kullanılan bir sınıf. Rect öğesi, SVG grafiklerinde dikdörtgenler oluşturmak için kullanılır. Bu sınıf, köşe yarıçapları ve boyutlar dahil olmak üzere rect öğesine özgü çeşitli öznitelikleri ayarlamak için yöntemler sağlar."
type: docs
weight: 1580
url: /tr/net/aspose.svg.builder/svgrectelementbuilder/
---
## SVGRectElementBuilder class

Builder class for constructing an SVG 'rect' element. The 'rect' element is used to create rectangles within SVG graphics. This class provides methods to set various attributes specific to the 'rect' element, including corner radii and dimensions.

```csharp
public class SVGRectElementBuilder : SVGElementBuilder<SVGRectElement>, IAnimationElementBuilder, 
    IDescriptiveElementBuilder, IPaintServerElementBuilder, IRectAttributeSetter, 
    IShapeAttributeSetter, IShapeContentElementBuilder
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGRectElementBuilder](svgrectelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGRectElement](../../aspose.svg/svgrectelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Rx](../../aspose.svg.builder/svgrectelementbuilder/rx/)(*double, [LengthType](../lengthtype/)*) | SVG 'rect' öğesinin 'rx' özniteliğini ayarlar, dikdörtgenin yuvarlatılmış köşelerinin yatay yarıçapını belirtir. |
| [Ry](../../aspose.svg.builder/svgrectelementbuilder/ry/)(*double, [LengthType](../lengthtype/)*) | SVG 'rect' öğesinin 'ry' özniteliğini ayarlar, dikdörtgenin yuvarlatılmış köşelerinin dikey yarıçapını belirtir. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGRectElement](../../aspose.svg/svgrectelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IShapeAttributeSetter](../ishapeattributesetter/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
