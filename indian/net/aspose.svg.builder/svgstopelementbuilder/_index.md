---
title: "SVGStopElementBuilder क्लास"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Builder.SVGStopElementBuilder क्लास। SVG स्टॉप एलिमेंट को बनाने के लिए बिल्डर क्लास। स्टॉप एलिमेंट का उपयोग ग्रेडिएंट परिभाषा में, चाहे रैखिक हो या रेडियल, रंग स्टॉप्स को परिभाषित करने के लिए किया जाता है। यह क्लास ऑफ़सेट और रंग जैसे स्टॉप एलिमेंट के विशिष्ट विभिन्न एट्रिब्यूट्स को सेट करने के लिए मेथड प्रदान करती है।"
type: docs
weight: 1620
url: /hi/net/aspose.svg.builder/svgstopelementbuilder/
---
## SVGStopElementBuilder class

SVG 'stop' तत्व बनाने के लिए Builder क्लास। 'stop' तत्व का उपयोग ग्रेडिएंट परिभाषा (रेखीय या रेडियल) के भीतर रंग स्टॉप्स को परिभाषित करने के लिए किया जाता है। यह क्लास 'stop' तत्व के विशिष्ट विभिन्न गुण सेट करने के लिए मेथड्स प्रदान करती है, जैसे ऑफसेट और रंग।

```csharp
public class SVGStopElementBuilder : SVGElementBuilder<SVGStopElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SVGStopElementBuilder](svgstopelementbuilder/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgstopelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | SVG 'stop' एलिमेंट में एक स्क्रिप्ट कॉन्फ़िगरेशन जोड़ता है। |
| [AddStyle](../../aspose.svg.builder/svgstopelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | SVG 'stop' एलिमेंट में एक स्टाइल कॉन्फ़िगरेशन जोड़ता है। |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStopElement](../../aspose.svg/svgstopelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Offset](../../aspose.svg.builder/svgstopelementbuilder/offset/)(*double, [StopUnitType](../stopunittype/)*) | SVG 'stop' एलिमेंट के 'offset' एट्रिब्यूट को सेट करता है, जो ग्रेडिएंट के भीतर रंग स्टॉप की स्थिति को निर्दिष्ट करता है। |

### संबंधित देखें

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStopElement](../../aspose.svg/svgstopelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
