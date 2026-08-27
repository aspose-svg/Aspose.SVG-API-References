---
title: "SVGSetElementBuilder क्लास"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Builder.SVGSetElementBuilder क्लास। निर्माण के लिए बिल्डर क्लास जो एक SVG सेट एलिमेंट बनाता है। सेट एलिमेंट का उपयोग एक सरल एनीमेशन को परिभाषित करने के लिए किया जाता है जहाँ एकल एट्रिब्यूट मान समय के एक अवधि में बदलता है। यह क्लास सेट एलिमेंट के विशिष्ट विभिन्न एट्रिब्यूट सेट करने के लिए मेथड प्रदान करता है, जैसे लक्ष्य एट्रिब्यूट और सेट करने के लिए मान।"
type: docs
weight: 1610
url: /hi/net/aspose.svg.builder/svgsetelementbuilder/
---
## SVGSetElementBuilder class

SVG 'set' तत्व बनाने के लिए Builder क्लास। 'set' तत्व का उपयोग एक सरल एनीमेशन को परिभाषित करने के लिए किया जाता है जहाँ एक ही गुण का मान समय के साथ बदलता है। यह क्लास 'set' तत्व के विशिष्ट विभिन्न गुण सेट करने के लिए मेथड्स प्रदान करती है, जैसे लक्ष्य गुण और सेट करने वाला मान।

```csharp
public class SVGSetElementBuilder : SVGElementBuilder<SVGSetElement>, 
    IAnimationEventAttributeSetter, IAnimationTargetAttributeSetter, 
    IAnimationTargetElementAttributeSetter, IAnimationTimingAttributeSetter, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SVGSetElementBuilder](svgsetelementbuilder/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGSetElement](../../aspose.svg/svgsetelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [To](../../aspose.svg.builder/svgsetelementbuilder/to/)(*string*) | SVG 'set' एलिमेंट के 'to' एट्रिब्यूट को सेट करता है, एनीमेशन के दौरान बदले जाने वाले एट्रिब्यूट का अंतिम मान निर्दिष्ट करता है। |

### संबंधित देखें

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
