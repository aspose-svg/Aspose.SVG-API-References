---
title: "SVGAElementBuilder Class"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Builder.SVGAElementBuilder क्लास। हाइपरलिंक परिभाषित करने के लिए उपयोग किए जाने वाले SVG a तत्व को बनाने के लिए बिल्डर क्लास। यह a तत्व के भीतर सामग्री बनाने को सक्षम बनाता है और SVG में a तत्व के विशिष्ट विभिन्न गुण सेट करने के लिए मेथड प्रदान करता है।"
type: docs
weight: 1070
url: /hi/net/aspose.svg.builder/svgaelementbuilder/
---
## SVGAElementBuilder class

SVG 'a' एलिमेंट को बनाने के लिए बिल्डर क्लास, जिसका उपयोग हाइपरलिंक परिभाषित करने के लिए किया जाता है। यह 'a' एलिमेंट के भीतर सामग्री बनाने को सक्षम करता है और SVG में 'a' एलिमेंट के विशिष्ट विभिन्न एट्रिब्यूट्स सेट करने के लिए मेथड्स प्रदान करता है।

```csharp
public class SVGAElementBuilder : SVGElementBuilder<SVGAElement>, ICompositeAttributeSetter, 
    ICompositeElementBuilder
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SVGAElementBuilder](svgaelementbuilder/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGAElement](../../aspose.svg/svgaelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Download](../../aspose.svg.builder/svgaelementbuilder/download/)(*string*) | SVG 'a' तत्व के 'download' एट्रिब्यूट को सेट करता है, यह दर्शाता है कि लिंक सक्रिय होने पर डाउनलोड किया जाएगा। |
| [Href](../../aspose.svg.builder/svgaelementbuilder/href/)(*string*) | SVG 'a' तत्व के 'href' एट्रिब्यूट को सेट करता है, लिंक किए गए संसाधन का URL निर्दिष्ट करता है। |
| [HrefLang](../../aspose.svg.builder/svgaelementbuilder/hreflang/)(*string*) | SVG 'a' तत्व के 'hreflang' एट्रिब्यूट को सेट करता है, लिंक किए गए संसाधन की भाषा दर्शाता है। |
| [Ping](../../aspose.svg.builder/svgaelementbuilder/ping/)(*string*) | SVG 'a' तत्व के 'ping' एट्रिब्यूट को सेट करता है, जिसमें लिंक का अनुसरण होने पर सूचित किए जाने वाले URL की सूची होती है। |
| [ReferrerPolicy](../../aspose.svg.builder/svgaelementbuilder/referrerpolicy/)(*[ReferrerPolicy](../referrerpolicy/)*) | SVG 'a' तत्व के 'referrerPolicy' एट्रिब्यूट को सेट करता है, यह निर्दिष्ट करता है कि अनुरोधों के साथ रेफ़रर का कितना हिस्सा भेजा जाए। |
| [Rel](../../aspose.svg.builder/svgaelementbuilder/rel/)(*string*) | SVG 'a' तत्व के 'rel' एट्रिब्यूट को सेट करता है, लक्ष्य वस्तु और लिंक वस्तु के बीच संबंध निर्दिष्ट करता है। |
| [SetTarget](../../aspose.svg.builder/svgaelementbuilder/settarget/)(*string*) | SVG 'a' तत्व के 'target' एट्रिब्यूट को एक कस्टम XML नाम पर सेट करता है। |
| [Type](../../aspose.svg.builder/svgaelementbuilder/type/)(*string*) | SVG 'a' तत्व के 'type' एट्रिब्यूट को सेट करता है, लिंक किए गए संसाधन का मीडिया प्रकार निर्दिष्ट करता है। |

### संबंधित देखें

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGAElement](../../aspose.svg/svgaelement/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
