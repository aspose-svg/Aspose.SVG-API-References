---
title: "SVGFEMorphologyElementBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGFEMorphologyElementBuilder sınıfı. Giriş görüntüsüne genişleme veya erozyon gibi morfolojik işlemler uygulamak için kullanılan SVG feMorphology öğelerini oluşturmak amacıyla tasarlanmış oluşturucu sınıf."
type: docs
weight: 1370
url: /tr/net/aspose.svg.builder/svgfemorphologyelementbuilder/
---
## SVGFEMorphologyElementBuilder class

Builder class for creating SVG 'feMorphology' elements, which are used to apply morphological operations like dilation or erosion on an input image.

```csharp
public class SVGFEMorphologyElementBuilder : SVGElementBuilder<SVGFEMorphologyElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGFEMorphologyElementBuilder](svgfemorphologyelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfemorphologyelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | feMorphology öğesine bir betik yapılandırması ekler. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEMorphologyElement](../../aspose.svg.filters/svgfemorphologyelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Operator](../../aspose.svg.builder/svgfemorphologyelementbuilder/operator/)(*[MorphologyOperator](../morphologyoperator/)*) | feMorphology öğesinin 'operator' özniteliğini ayarlar, morfolojik işlemin türünü belirtir. |
| [Radius](../../aspose.svg.builder/svgfemorphologyelementbuilder/radius/)(*double, double?*) | feMorphology öğesinin 'radius' özniteliğini ayarlar, morfolojik işlem için yarıçapı tanımlar. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEMorphologyElement](../../aspose.svg.filters/svgfemorphologyelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
