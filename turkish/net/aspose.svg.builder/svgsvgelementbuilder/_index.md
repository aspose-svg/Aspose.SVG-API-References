---
title: "SVGSVGElementBuilder Class"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGSVGElementBuilder class. Bir SVG belgesinin kök öğesi olan SVGSVGElement'i oluşturmak için kullanılan yapı sınıfı."
type: docs
weight: 1590
url: /tr/net/aspose.svg.builder/svgsvgelementbuilder/
---
## SVGSVGElementBuilder class

SVGSVGElement'i oluşturmak için bir builder sınıfı, bir SVG belgesinin kök öğesidir.

```csharp
public class SVGSVGElementBuilder : SVGElementBuilder<SVGSVGElement>, ICompositeAttributeSetter, 
    ICompositeElementBuilder, IDocumentEventAttributeSetter, IPreserveAspectRatioAttributeSetter, 
    IRectAttributeSetter, IViewBoxAttributeSetter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGSVGElementBuilder](svgsvgelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| [BaseProfile](../../aspose.svg.builder/svgsvgelementbuilder/baseprofile/)(*double*) | SVG öğesinin 'baseProfile' özniteliğini ayarlar. Bu öznitelik, tam SVG spesifikasyonunun hangi alt kümesinin belgeye uygulandığını gösterir. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGSVGElement](../../aspose.svg/svgsvgelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [ContentScriptType](../../aspose.svg.builder/svgsvgelementbuilder/contentscripttype/)(*string*) | SVG öğesinin 'contentScriptType' özniteliğini ayarlar. Bu öznitelik, SVG belgesinin içeriği için varsayılan betik dilini belirtir. |
| [ContentStyleType](../../aspose.svg.builder/svgsvgelementbuilder/contentstyletype/)(*string*) | SVG öğesinin 'contentStyleType' özniteliğini ayarlar. Bu öznitelik, SVG belgesinin içeriği için varsayılan stil dilini belirtir. |
| [Version](../../aspose.svg.builder/svgsvgelementbuilder/version/)(*double*) | SVG öğesinin 'version' özniteliğini ayarlar. Bu öznitelik, belgenin uyduğu SVG spesifikasyon sürümünü belirtir. |
| [WithXlink](../../aspose.svg.builder/svgsvgelementbuilder/withxlink/)() | SVG öğesine XLink ad alanı bildirimini ekler. Bu, 'xlink:href' gibi XLink özniteliklerini kullanmak için gereklidir. |
| [ZoomAndPan](../../aspose.svg.builder/svgsvgelementbuilder/zoomandpan/)(*string*) | SVG öğesinin 'zoomAndPan' özniteliğini ayarlar. Bu öznitelik, SVG içeriğinin yakınlaştırılıp kaydırılıp kaydırılamayacağını kontrol eder. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGSVGElement](../../aspose.svg/svgsvgelement/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [IDocumentEventAttributeSetter](../idocumenteventattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
