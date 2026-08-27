---
title: "SVGScriptElementBuilder क्लास"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Builder.SVGScriptElementBuilder क्लास। SVG script तत्व बनाने के लिए Builder क्लास। script तत्व का उपयोग SVG दस्तावेज़ों में निष्पादन योग्य स्क्रिप्ट को एम्बेड या संदर्भित करने के लिए किया जाता है। यह क्लास script तत्व के विशिष्ट विभिन्न एट्रिब्यूट जैसे type, source और cross-origin सेटिंग्स को सेट करने के लिए मेथड प्रदान करती है।"
type: docs
weight: 1600
url: /hi/net/aspose.svg.builder/svgscriptelementbuilder/
---
## SVGScriptElementBuilder class

SVG 'script' तत्व बनाने के लिए Builder क्लास। 'script' तत्व का उपयोग SVG दस्तावेज़ों में निष्पादन योग्य स्क्रिप्ट को एम्बेड या संदर्भित करने के लिए किया जाता है। यह क्लास 'script' तत्व के विशिष्ट विभिन्न गुण सेट करने के लिए मेथड्स प्रदान करती है, जैसे प्रकार, स्रोत, और क्रॉस-ऑरिजिन सेटिंग्स।

```csharp
public class SVGScriptElementBuilder : SVGElementBuilder<SVGScriptElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SVGScriptElementBuilder](svgscriptelementbuilder/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGScriptElement](../../aspose.svg/svgscriptelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Crossorigin](../../aspose.svg.builder/svgscriptelementbuilder/crossorigin/)(*string*) | SVG 'script' तत्व के 'crossorigin' एट्रिब्यूट को सेट करता है, बाहरी स्क्रिप्ट के लिए CORS सेटिंग्स निर्दिष्ट करता है। |
| [Href](../../aspose.svg.builder/svgscriptelementbuilder/href/)(*string*) | SVG 'script' तत्व के 'href' एट्रिब्यूट को सेट करता है, बाहरी स्क्रिप्ट फ़ाइल का URL निर्दिष्ट करता है। |
| [Type](../../aspose.svg.builder/svgscriptelementbuilder/type/)(*string*) | SVG 'script' तत्व के 'type' एट्रिब्यूट को सेट करता है, स्क्रिप्टिंग भाषा प्रकार निर्दिष्ट करता है (उदाहरण के लिए, "text/javascript"). |

### संबंधित देखें

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGScriptElement](../../aspose.svg/svgscriptelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
