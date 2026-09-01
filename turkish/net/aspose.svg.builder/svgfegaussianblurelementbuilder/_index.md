---
title: "SVGFEGaussianBlurElementBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGFEGaussianBlurElementBuilder sınıfı. Gaussian bulanıklaştırma filtresi etkisi uygulayan SVG feGaussianBlur öğelerini oluşturmak için kullanılan oluşturucu sınıf."
type: docs
weight: 1330
url: /tr/net/aspose.svg.builder/svgfegaussianblurelementbuilder/
---
## SVGFEGaussianBlurElementBuilder class

SVG 'feGaussianBlur' öğelerini oluşturmak için Builder sınıfı, Gaussian bulanıklaştırma filtresi etkisini uygular.

```csharp
public class SVGFEGaussianBlurElementBuilder : SVGElementBuilder<SVGFEGaussianBlurElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGFEGaussianBlurElementBuilder](svgfegaussianblurelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfegaussianblurelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | feGaussianBlur öğesine bir betik yapılandırması ekler. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEGaussianBlurElement](../../aspose.svg.filters/svgfegaussianblurelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [StdDeviation](../../aspose.svg.builder/svgfegaussianblurelementbuilder/stddeviation/)(*double, double?*) | Gaussian bulanıklaştırma etkisi için standart sapmayı ayarlar. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEGaussianBlurElement](../../aspose.svg.filters/svgfegaussianblurelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
