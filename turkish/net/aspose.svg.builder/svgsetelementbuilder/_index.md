---
title: "SVGSetElementBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGSetElementBuilder sınıf. SVG set öğesi oluşturmak için kullanılan oluşturucu sınıf. Set öğesi, tek bir öznitelik değerinin bir zaman diliminde değiştiği basit bir animasyonu tanımlamak için kullanılır. Bu sınıf, hedef öznitelik ve ayarlanacak değer gibi set öğesine özgü çeşitli öznitelikleri ayarlamak için yöntemler sağlar."
type: docs
weight: 1610
url: /tr/net/aspose.svg.builder/svgsetelementbuilder/
---
## SVGSetElementBuilder class

SVG 'set' öğesini oluşturmak için Builder sınıfı. 'set' öğesi, tek bir öznitelik değerinin belirli bir süre içinde değiştiği basit bir animasyonu tanımlamak için kullanılır. Bu sınıf, 'set' öğesine özgü çeşitli öznitelikleri ayarlamak için yöntemler sağlar, örneğin hedef öznitelik ve ayarlanacak değer.

```csharp
public class SVGSetElementBuilder : SVGElementBuilder<SVGSetElement>, 
    IAnimationEventAttributeSetter, IAnimationTargetAttributeSetter, 
    IAnimationTargetElementAttributeSetter, IAnimationTimingAttributeSetter, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGSetElementBuilder](svgsetelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGSetElement](../../aspose.svg/svgsetelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [To](../../aspose.svg.builder/svgsetelementbuilder/to/)(*string*) | SVG 'set' öğesinin 'to' özniteliğini ayarlar ve animasyon sırasında değişecek öznitelik için son değeri belirtir. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGSetElement](../../aspose.svg/svgsetelement/)
* interface [IAnimationEventAttributeSetter](../ianimationeventattributesetter/)
* interface [IAnimationTargetAttributeSetter](../ianimationtargetattributesetter/)
* interface [IAnimationTargetElementAttributeSetter](../ianimationtargetelementattributesetter/)
* interface [IAnimationTimingAttributeSetter](../ianimationtimingattributesetter/)
* interface [IConditionalProcessingAttributeSetter](../iconditionalprocessingattributesetter/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
