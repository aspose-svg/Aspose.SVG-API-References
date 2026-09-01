---
title: "SVGLinearGradientElementBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGLinearGradientElementBuilder sınıfı. SVG linearGradient öğesini oluşturmak için kullanılan bir builder sınıfı. Bu sınıf, linearGradient öğesi içinde içerik oluşturmayı sağlar ve SVG'de linearGradient öğesine özgü çeşitli öznitelikleri ayarlamak için yöntemler sunar."
type: docs
weight: 1490
url: /tr/net/aspose.svg.builder/svglineargradientelementbuilder/
---
## SVGLinearGradientElementBuilder class

SVG 'linearGradient' öğesini oluşturmak için Builder sınıfı, bu öğe SVG grafiklerinde doğrusal bir degrade tanımlamak için kullanılır. 'linearGradient' öğesi içinde içerik oluşturmayı sağlar ve SVG'de 'linearGradient' öğesine özgü çeşitli öznitelikleri ayarlamak için yöntemler sunar.

```csharp
public class SVGLinearGradientElementBuilder : SVGElementBuilder<SVGLinearGradientElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, IGradientStopElementBuilder, 
    IPresentationAttributeSetter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGLinearGradientElementBuilder](svglineargradientelementbuilder/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddAnimateTransform](../../aspose.svg.builder/svglineargradientelementbuilder/addanimatetransform/)(*Action&lt;SVGAnimateTransformElementBuilder&gt;*) | SVG 'linearGradient' öğesine bir animate transform yapılandırması ekler. |
| [AddScript](../../aspose.svg.builder/svglineargradientelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | SVG 'linearGradient' öğesine bir script yapılandırması ekler. |
| [AddStyle](../../aspose.svg.builder/svglineargradientelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | SVG 'linearGradient' öğesine bir style yapılandırması ekler. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGLinearGradientElement](../../aspose.svg/svglineargradientelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svglineargradientelementbuilder/href/)(*string*) | SVG 'linearGradient' öğesinin 'href' özniteliğini ayarlar, başka bir degradeye referans belirtir. |
| [X1](../../aspose.svg.builder/svglineargradientelementbuilder/x1/)(*double, [LengthType](../lengthtype/)*) | SVG 'linearGradient' öğesinin 'x1' özniteliğini ayarlar, degrade başlangıç noktasının x koordinatını belirtir. |
| [X2](../../aspose.svg.builder/svglineargradientelementbuilder/x2/)(*double, [LengthType](../lengthtype/)*) | SVG 'linearGradient' öğesinin 'x2' özniteliğini ayarlar, degrade bitiş noktasının x koordinatını belirtir. |
| [Y1](../../aspose.svg.builder/svglineargradientelementbuilder/y1/)(*double, [LengthType](../lengthtype/)*) | SVG 'linearGradient' öğesinin 'y1' özniteliğini ayarlar, degrade başlangıç noktasının y koordinatını belirtir. |
| [Y2](../../aspose.svg.builder/svglineargradientelementbuilder/y2/)(*double, [LengthType](../lengthtype/)*) | SVG 'linearGradient' öğesinin 'y2' özniteliğini ayarlar, degrade bitiş noktasının y koordinatını belirtir. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGLinearGradientElement](../../aspose.svg/svglineargradientelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IGradientStopElementBuilder](../igradientstopelementbuilder/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
