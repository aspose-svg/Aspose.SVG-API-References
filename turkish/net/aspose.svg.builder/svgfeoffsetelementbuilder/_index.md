---
title: "SVGFEOffsetElementBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGFEOffsetElementBuilder sınıfı. Giriş görüntüsüne bir offset etkisi uygulamak için kullanılan SVG feOffset öğelerini oluşturmak için bir builder sınıfı."
type: docs
weight: 1380
url: /tr/net/aspose.svg.builder/svgfeoffsetelementbuilder/
---
## SVGFEOffsetElementBuilder class

Builder class for creating SVG 'feOffset' elements, which are used to apply an offset effect to an input image.

```csharp
public class SVGFEOffsetElementBuilder : SVGElementBuilder<SVGFEOffsetElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGFEOffsetElementBuilder](svgfeoffsetelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfeoffsetelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | feOffset öğesine bir script yapılandırması ekler. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEOffsetElement](../../aspose.svg.filters/svgfeoffsetelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Dx](../../aspose.svg.builder/svgfeoffsetelementbuilder/dx/)(*double*) | feOffset öğesinin 'dx' özniteliğini ayarlar, yatay offseti belirler. |
| [Dy](../../aspose.svg.builder/svgfeoffsetelementbuilder/dy/)(*double*) | feOffset öğesinin 'dy' özniteliğini ayarlar, dikey offseti belirler. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEOffsetElement](../../aspose.svg.filters/svgfeoffsetelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
