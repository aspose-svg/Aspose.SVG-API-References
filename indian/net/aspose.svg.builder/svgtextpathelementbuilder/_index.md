---
title: "SVGTextPathElementBuilder क्लास"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Builder.SVGTextPathElementBuilder क्लास। SVG textPath एलिमेंट बनाने के लिए बिल्डर क्लास, जिसका उपयोग टेक्स्ट को पाथ के साथ संरेखित करने के लिए किया जाता है"
type: docs
weight: 1680
url: /hi/net/aspose.svg.builder/svgtextpathelementbuilder/
---
## SVGTextPathElementBuilder class

SVG 'textPath' तत्व बनाने के लिए Builder क्लास, जिसका उपयोग टेक्स्ट को पाथ के साथ संरेखित करने के लिए किया जाता है।

```csharp
public class SVGTextPathElementBuilder : SVGElementBuilder<SVGTextPathElement>, 
    IBaseAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IPaintServerElementBuilder, IShapeContentElementBuilder, ITextContentSetter
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SVGTextPathElementBuilder](svgtextpathelementbuilder/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddA](../../aspose.svg.builder/svgtextpathelementbuilder/adda/)(*Action&lt;SVGAElementBuilder&gt;*) | 'textPath' में एक 'a' (एंकर) एलिमेंट कॉन्फ़िगरेशन जोड़ता है। |
| [AddTSpan](../../aspose.svg.builder/svgtextpathelementbuilder/addtspan/)(*Action&lt;SVGTSpanElementBuilder&gt;*) | 'textPath' में एक 'tspan' एलिमेंट कॉन्फ़िगरेशन जोड़ता है। |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGTextPathElement](../../aspose.svg/svgtextpathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgtextpathelementbuilder/href/)(*string*) | 'href' एट्रिब्यूट सेट करता है, जो एक पाथ एलिमेंट का संदर्भ निर्दिष्ट करता है। |
| [LengthAdjust](../../aspose.svg.builder/svgtextpathelementbuilder/lengthadjust/)(*[LengthAdjust](../lengthadjust/)*) | 'lengthAdjust' एट्रिब्यूट सेट करता है, जो टेक्स्ट लंबाई समायोजन कैसे किया जाता है, इसे निर्दिष्ट करता है। |
| [Method](../../aspose.svg.builder/svgtextpathelementbuilder/method/)(*[TextPathMethod](../textpathmethod/)*) | 'method' एट्रिब्यूट सेट करता है, जो पाथ के साथ टेक्स्ट लेआउट विधि को निर्दिष्ट करता है। |
| [Path](../../aspose.svg.builder/svgtextpathelementbuilder/path/)(*Action&lt;PathBuilder&gt;*) | टेक्स्ट के लिए पाथ को कॉन्फ़िगर करता है। |
| [Side](../../aspose.svg.builder/svgtextpathelementbuilder/side/)(*[HorizontalEdge](../horizontaledge/)*) | 'side' एट्रिब्यूट सेट करता है, जो यह निर्दिष्ट करता है कि टेक्स्ट पाथ के किस पक्ष पर रखा गया है। |
| [Spacing](../../aspose.svg.builder/svgtextpathelementbuilder/spacing/)(*[TextPathSpacing](../textpathspacing/)*) | पाथ के साथ टेक्स्ट के लिए स्पेसिंग रणनीति निर्दिष्ट करते हुए, 'spacing' एट्रिब्यूट सेट करता है। |
| [StartOffset](../../aspose.svg.builder/svgtextpathelementbuilder/startoffset/)(*double, [LengthType](../lengthtype/)*) | पाथ पर टेक्स्ट की प्रारंभिक स्थिति निर्दिष्ट करते हुए, 'startOffset' एट्रिब्यूट सेट करता है। |
| [TextLength](../../aspose.svg.builder/svgtextpathelementbuilder/textlength/)(*double, [LengthType](../lengthtype/)*) | टेक्स्ट की लंबाई निर्दिष्ट करते हुए, 'textLength' एट्रिब्यूट सेट करता है। |

### संबंधित देखें

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGTextPathElement](../../aspose.svg/svgtextpathelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* interface [ITextContentSetter](../itextcontentsetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
