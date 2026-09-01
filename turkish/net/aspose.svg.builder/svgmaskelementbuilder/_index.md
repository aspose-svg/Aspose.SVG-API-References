---
title: "SVGMaskElementBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGMaskElementBuilder sınıfı. Mevcut nesneyi arka plana birleştirmek için alfa maskesi tanımlamak amacıyla bir SVG maske öğesi oluşturmak için kullanılan bir yapıcı sınıf. Bu sınıf, maske öğesi içinde içerik oluşturmayı sağlar ve SVG'deki maske öğesine özgü çeşitli özellikleri ayarlamak için yöntemler sunar."
type: docs
weight: 1510
url: /tr/net/aspose.svg.builder/svgmaskelementbuilder/
---
## SVGMaskElementBuilder class

SVG 'mask' öğesini oluşturmak için Builder sınıfı, bu öğe mevcut nesneyi arka plana birleştirmek için bir alfa maskesi tanımlamakta kullanılır. 'mask' öğesi içinde içerik oluşturmayı sağlar ve SVG'de 'mask' öğesine özgü çeşitli öznitelikleri ayarlamak için yöntemler sunar.

```csharp
public class SVGMaskElementBuilder : SVGElementBuilder<SVGMaskElement>, ICompositeElementBuilder, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IRectAttributeSetter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGMaskElementBuilder](svgmaskelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMaskElement](../../aspose.svg/svgmaskelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MaskContentUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskcontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | SVG 'mask' öğesinin 'maskContentUnits' özelliğini ayarlar, maskenin içeriği için koordinat sistemini belirtir. |
| [MaskUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskunits/)(*[CoordinateUnits](../coordinateunits/)*) | SVG 'mask' öğesinin 'maskUnits' özelliğini ayarlar, maskenin özellikleri için koordinat sistemini belirtir. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGMaskElement](../../aspose.svg/svgmaskelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../iconditionalprocessingattributesetter/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
