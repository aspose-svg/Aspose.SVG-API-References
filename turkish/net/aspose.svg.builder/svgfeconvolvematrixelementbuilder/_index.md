---
title: "SVGFEConvolveMatrixElementBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGFEConvolveMatrixElementBuilder sınıfı. SVG filtrelerinde konvolüsyon matris etkilerini uygulamak için kullanılan SVG feConvolveMatrix öğelerini oluşturmak amacıyla bir builder sınıfı."
type: docs
weight: 1230
url: /tr/net/aspose.svg.builder/svgfeconvolvematrixelementbuilder/
---
## SVGFEConvolveMatrixElementBuilder class

SVG 'feConvolveMatrix' öğelerini oluşturmak için oluşturucu sınıf, konvolüsyon matris etkilerini uygulamak için SVG filtrelerinde kullanılır.

```csharp
public class SVGFEConvolveMatrixElementBuilder : SVGElementBuilder<SVGFEConvolveMatrixElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGFEConvolveMatrixElementBuilder](svgfeconvolvematrixelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Öğeye bir script yapılandırması ekler. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| [Bias](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/bias/)(*double*) | feConvolveMatrix öğesinin 'bias' özniteliğini ayarlar. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEConvolveMatrixElement](../../aspose.svg.filters/svgfeconvolvematrixelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Divisor](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/divisor/)(*double*) | feConvolveMatrix öğesinin 'divisor' özniteliğini ayarlar. |
| [EdgeMode](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/edgemode/)(*[EdgeMode](../edgemode/)*) | feConvolveMatrix öğesinin 'edgeMode' özniteliğini ayarlar. |
| [KernelMatrix](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/kernelmatrix/)(*params double[]*) | feConvolveMatrix öğesinin 'kernelMatrix' özniteliğini ayarlar. |
| [KernelUnitLength](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/kernelunitlength/)(*double, double?*) | feConvolveMatrix öğesinin 'kernelUnitLength' özniteliğini ayarlar. |
| [Order](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/order/)(*int, int?*) | feConvolveMatrix öğesinin 'order' özniteliğini ayarlar. |
| [PreserveAlpha](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/preservealpha/)(*bool*) | feConvolveMatrix öğesinin 'preserveAlpha' özniteliğini ayarlar. |
| [TargetX](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/targetx/)(*int*) | feConvolveMatrix öğesinin 'targetX' özniteliğini ayarlar. |
| [TargetY](../../aspose.svg.builder/svgfeconvolvematrixelementbuilder/targety/)(*int*) | feConvolveMatrix öğesinin 'targetY' özniteliğini ayarlar. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEConvolveMatrixElement](../../aspose.svg.filters/svgfeconvolvematrixelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
