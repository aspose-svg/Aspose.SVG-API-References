---
title: "SVGFEBaseLightingElementBuilderTElementTBuilder Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGFEBaseLightingElementBuilder2TElementTBuilder sınıfı. SVG filtre efekti aydınlatma öğeleri oluşturucular için soyut temel sınıf"
type: docs
weight: 1180
url: /tr/net/aspose.svg.builder/svgfebaselightingelementbuilder-2/
---
## SVGFEBaseLightingElementBuilder<TElement,TBuilder> class

SVG filter effect lighting elements oluşturucuları için soyut temel sınıf.

```csharp
public abstract class SVGFEBaseLightingElementBuilder<TElement, TBuilder> : 
    SVGElementBuilder<TElement>, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
    where TElement : SVGElement
    where TBuilder : SVGFEBaseLightingElementBuilder
```

| Parametre | Açıklama |
| --- | --- |
| TElement | Oluşturulan SVG öğesinin türü. |
| TBuilder | Oluşturucunun kendisinin türü. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Öğeye bir script yapılandırması ekler. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | SVG öğesini oluşturur, belirtilmişse ışık kaynağı yapılandırmasını uygular. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*TElement*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [WithFeDistantLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfedistantlight/)(*Action&lt;SVGFEDistantLightElementBuilder&gt;*) | Filtre etkisi için uzak bir ışık kaynağını yapılandırır. |
| [WithFePointLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfepointlight/)(*Action&lt;SVGFEPointLightElementBuilder&gt;*) | Filtre etkisi için nokta ışık kaynağını yapılandırır. |
| [WithFeSpotLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfespotlight/)(*Action&lt;SVGFESpotLightElementBuilder&gt;*) | Filtre etkisi için spot ışık kaynağını yapılandırır. |

### Ayrıca Bakınız

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
