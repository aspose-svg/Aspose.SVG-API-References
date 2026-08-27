---
title: "SVGLinearGradientElementBuilder क्लास"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Builder.SVGLinearGradientElementBuilder क्लास। SVG linearGradient तत्व को बनाने के लिए Builder क्लास, जिसका उपयोग SVG ग्राफिक्स में एक रैखिक ग्रेडिएंट को परिभाषित करने के लिए किया जाता है। यह linearGradient तत्व के भीतर सामग्री बनाने को सक्षम करता है और SVG में linearGradient तत्व के विशिष्ट विभिन्न गुणों को सेट करने के लिए मेथड्स प्रदान करता है।"
type: docs
weight: 1490
url: /hi/net/aspose.svg.builder/svglineargradientelementbuilder/
---
## SVGLinearGradientElementBuilder class

SVG 'linearGradient' तत्व बनाने के लिए Builder क्लास, जो SVG ग्राफ़िक्स में एक रैखिक ग्रेडिएंट को परिभाषित करने के लिए उपयोग की जाती है। यह 'linearGradient' तत्व के भीतर सामग्री बनाने को सक्षम करती है और SVG में 'linearGradient' तत्व के विशिष्ट विभिन्न एट्रिब्यूट सेट करने के लिए मेथड्स प्रदान करती है।

```csharp
public class SVGLinearGradientElementBuilder : SVGElementBuilder<SVGLinearGradientElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, IGradientStopElementBuilder, 
    IPresentationAttributeSetter
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SVGLinearGradientElementBuilder](svglineargradientelementbuilder/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddAnimateTransform](../../aspose.svg.builder/svglineargradientelementbuilder/addanimatetransform/)(*Action&lt;SVGAnimateTransformElementBuilder&gt;*) | SVG 'linearGradient' तत्व में एक animate transform कॉन्फ़िगरेशन जोड़ता है। |
| [AddScript](../../aspose.svg.builder/svglineargradientelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | SVG 'linearGradient' तत्व में एक script कॉन्फ़िगरेशन जोड़ता है। |
| [AddStyle](../../aspose.svg.builder/svglineargradientelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | SVG 'linearGradient' तत्व में एक style कॉन्फ़िगरेशन जोड़ता है। |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGLinearGradientElement](../../aspose.svg/svglineargradientelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svglineargradientelementbuilder/href/)(*string*) | SVG 'linearGradient' तत्व का 'href' एट्रिब्यूट सेट करता है, जो किसी अन्य ग्रेडिएंट का संदर्भ निर्दिष्ट करता है। |
| [X1](../../aspose.svg.builder/svglineargradientelementbuilder/x1/)(*double, [LengthType](../lengthtype/)*) | SVG 'linearGradient' तत्व का 'x1' एट्रिब्यूट सेट करता है, जो ग्रेडिएंट के प्रारंभ बिंदु का x-निर्देशांक निर्दिष्ट करता है। |
| [X2](../../aspose.svg.builder/svglineargradientelementbuilder/x2/)(*double, [LengthType](../lengthtype/)*) | SVG 'linearGradient' तत्व का 'x2' एट्रिब्यूट सेट करता है, जो ग्रेडिएंट के अंत बिंदु का x-निर्देशांक निर्दिष्ट करता है। |
| [Y1](../../aspose.svg.builder/svglineargradientelementbuilder/y1/)(*double, [LengthType](../lengthtype/)*) | SVG 'linearGradient' तत्व का 'y1' एट्रिब्यूट सेट करता है, जो ग्रेडिएंट के प्रारंभ बिंदु का y-निर्देशांक निर्दिष्ट करता है। |
| [Y2](../../aspose.svg.builder/svglineargradientelementbuilder/y2/)(*double, [LengthType](../lengthtype/)*) | SVG 'linearGradient' तत्व का 'y2' एट्रिब्यूट सेट करता है, जो ग्रेडिएंट के अंत बिंदु का y-निर्देशांक निर्दिष्ट करता है। |

### संबंधित देखें

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
