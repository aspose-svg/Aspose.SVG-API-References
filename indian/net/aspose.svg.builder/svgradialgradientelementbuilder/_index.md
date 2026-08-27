---
title: "SVGRadialGradientElementBuilder क्लास"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Builder.SVGRadialGradientElementBuilder क्लास। SVG ग्राफिक्स के भीतर रेडियल ग्रेडिएंट को परिभाषित करने के लिए उपयोग किए जाने वाले SVG radialGradient तत्व को बनाने के लिए बिल्डर क्लास। यह क्लास radialGradient तत्व के भीतर सामग्री बनाने को सक्षम करती है और SVG में radialGradient तत्व के विशिष्ट विभिन्न एट्रिब्यूट सेट करने के लिए मेथड्स प्रदान करती है।"
type: docs
weight: 1570
url: /hi/net/aspose.svg.builder/svgradialgradientelementbuilder/
---
## SVGRadialGradientElementBuilder class

SVG 'radialGradient' तत्व बनाने के लिए Builder क्लास, जिसका उपयोग SVG ग्राफिक्स में रेडियल ग्रेडिएंट परिभाषित करने के लिए किया जाता है। यह क्लास 'radialGradient' तत्व के भीतर सामग्री बनाने को सक्षम करती है और SVG में 'radialGradient' तत्व के विशिष्ट विभिन्न गुण सेट करने के लिए मेथड्स प्रदान करती है।

```csharp
public class SVGRadialGradientElementBuilder : SVGElementBuilder<SVGRadialGradientElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, IGradientStopElementBuilder, 
    IPresentationAttributeSetter
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SVGRadialGradientElementBuilder](svgradialgradientelementbuilder/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddAnimateTransform](../../aspose.svg.builder/svgradialgradientelementbuilder/addanimatetransform/)(*Action&lt;SVGAnimateTransformElementBuilder&gt;*) | SVG 'radialGradient' तत्व में एक एनीमेट ट्रांसफ़ॉर्म कॉन्फ़िगरेशन जोड़ता है। |
| [AddScript](../../aspose.svg.builder/svgradialgradientelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | SVG 'radialGradient' तत्व में एक स्क्रिप्ट कॉन्फ़िगरेशन जोड़ता है। |
| [AddStyle](../../aspose.svg.builder/svgradialgradientelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | SVG 'radialGradient' तत्व में एक स्टाइल कॉन्फ़िगरेशन जोड़ता है। |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGRadialGradientElement](../../aspose.svg/svgradialgradientelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Cx](../../aspose.svg.builder/svgradialgradientelementbuilder/cx/)(*double, [LengthType](../lengthtype/)*) | SVG 'radialGradient' तत्व के 'cx' एट्रिब्यूट को सेट करता है, जो ग्रेडिएंट के केंद्र के x-निर्देशांक को निर्दिष्ट करता है। |
| [Cy](../../aspose.svg.builder/svgradialgradientelementbuilder/cy/)(*double, [LengthType](../lengthtype/)*) | SVG 'radialGradient' तत्व के 'cy' एट्रिब्यूट को सेट करता है, जो ग्रेडिएंट के केंद्र के y-निर्देशांक को निर्दिष्ट करता है। |
| [Fx](../../aspose.svg.builder/svgradialgradientelementbuilder/fx/)(*double, [LengthType](../lengthtype/)*) | SVG 'radialGradient' तत्व के 'fx' एट्रिब्यूट को सेट करता है, जो ग्रेडिएंट के फोकल पॉइंट के x-निर्देशांक को निर्दिष्ट करता है। |
| [Fy](../../aspose.svg.builder/svgradialgradientelementbuilder/fy/)(*double, [LengthType](../lengthtype/)*) | SVG 'radialGradient' तत्व के 'fy' एट्रिब्यूट को सेट करता है, जो ग्रेडिएंट के फोकल पॉइंट के y-निर्देशांक को निर्दिष्ट करता है। |
| [Href](../../aspose.svg.builder/svgradialgradientelementbuilder/href/)(*string*) | SVG 'radialGradient' तत्व के 'href' एट्रिब्यूट को सेट करता है, जो किसी अन्य ग्रेडिएंट का संदर्भ निर्दिष्ट करता है। |
| [R](../../aspose.svg.builder/svgradialgradientelementbuilder/r/)(*double, [LengthType](../lengthtype/)*) | SVG 'radialGradient' तत्व के 'r' एट्रिब्यूट को सेट करता है, जो ग्रेडिएंट की त्रिज्या को निर्दिष्ट करता है। |

### संबंधित देखें

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGRadialGradientElement](../../aspose.svg/svgradialgradientelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IGradientStopElementBuilder](../igradientstopelementbuilder/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
