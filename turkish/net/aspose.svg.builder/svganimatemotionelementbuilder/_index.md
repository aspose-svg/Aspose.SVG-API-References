---
title: "SVGAnimateMotionElementBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGAnimateMotionElementBuilder sınıfı. SVG grafiklerinde hareket animasyonları oluşturmak için kullanılan bir SVG animateMotion öğesi oluşturmak için yapılandırıcı sınıf. animateMotion öğesi içinde içerik oluşturmayı sağlar ve SVG'deki animateMotion öğesine özgü çeşitli öznitelikleri ayarlamak için yöntemler sunar."
type: docs
weight: 1090
url: /tr/net/aspose.svg.builder/svganimatemotionelementbuilder/
---
## SVGAnimateMotionElementBuilder class

SVG grafiklerinde hareket animasyonları oluşturmak için kullanılan SVG 'animateMotion' öğesini oluşturmak için bir oluşturucu sınıfı. 'animateMotion' öğesi içinde içerik oluşturmayı sağlar ve SVG'deki 'animateMotion' öğesine özgü çeşitli öznitelikleri ayarlamak için yöntemler sunar.

```csharp
public class SVGAnimateMotionElementBuilder : SVGElementBuilder<SVGAnimateMotionElement>, 
    IAnimationAdditionAttributeSetter, IAnimationEventAttributeSetter, 
    IAnimationTargetElementAttributeSetter, IAnimationTimingAttributeSetter, 
    IAnimationValueAttributeSetter, IConditionalProcessingAttributeSetter, ICoreAttributeSetter, 
    IDescriptiveElementBuilder, IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IXLinkAttributeSetter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGAnimateMotionElementBuilder](svganimatemotionelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGAnimateMotionElement](../../aspose.svg/svganimatemotionelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [KeyPoints](../../aspose.svg.builder/svganimatemotionelementbuilder/keypoints/)(*params double[]*) | 'keyPoints' özniteliğini ayarlar, animasyonun gerçekleştiği noktaları tanımlar. |
| [Path](../../aspose.svg.builder/svganimatemotionelementbuilder/path/)(*Action&lt;PathBuilder&gt;*) | Hareket animasyonu için yolu tanımlar. |
| [Rotate](../../aspose.svg.builder/svganimatemotionelementbuilder/rotate/#rotate_1)(*double*) | 'rotate' özniteliğini ayarlar, animasyonlu öğenin dönüşünü tanımlar. |
| [Rotate](../../aspose.svg.builder/svganimatemotionelementbuilder/rotate/#rotate)(*[Rotate](../rotate/)*) | 'rotate' özniteliğini önceden tanımlı bir dönüş değeri kullanarak ayarlar. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGAnimateMotionElement](../../aspose.svg/svganimatemotionelement/)
* interface [IAnimationAdditionAttributeSetter](../ianimationadditionattributesetter/)
* interface [IAnimationEventAttributeSetter](../ianimationeventattributesetter/)
* interface [IAnimationTargetElementAttributeSetter](../ianimationtargetelementattributesetter/)
* interface [IAnimationTimingAttributeSetter](../ianimationtimingattributesetter/)
* interface [IAnimationValueAttributeSetter](../ianimationvalueattributesetter/)
* interface [IConditionalProcessingAttributeSetter](../iconditionalprocessingattributesetter/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IXLinkAttributeSetter](../ixlinkattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
