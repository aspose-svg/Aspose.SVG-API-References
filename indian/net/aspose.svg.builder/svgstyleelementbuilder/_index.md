---
title: "SVGStyleElementBuilder Class"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Builder.SVGStyleElementBuilder class. SVG शैली तत्व बनाने के लिए एक बिल्डर क्लास। यह क्लास CSS नियमों के साथ SVG शैली तत्व के निर्माण और कॉन्फ़िगरेशन को आसान बनाती है।"
type: docs
weight: 1630
url: /hi/net/aspose.svg.builder/svgstyleelementbuilder/
---
## SVGStyleElementBuilder class

SVG 'style' तत्व बनाने के लिए एक Builder क्लास। यह क्लास CSS नियमों के साथ SVG स्टाइल तत्व के निर्माण और कॉन्फ़िगरेशन को आसान बनाती है।

```csharp
public class SVGStyleElementBuilder : SVGElementBuilder<SVGStyleElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SVGStyleElementBuilder](svgstyleelementbuilder/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddComment](../../aspose.svg.builder/svgstyleelementbuilder/addcomment/)(*string*) | स्टाइल सामग्री में एक टिप्पणी जोड़ता है। |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule)(*string, Action&lt;RuleBuilder&gt;*) | RuleBuilder का उपयोग करके शैली तत्व में एक CSS नियम जोड़ता है। |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule_1)(*string, string*) | शैली तत्व में एक CSS नियम जोड़ता है। |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgstyleelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | संचित CSS नियमों के साथ SVG शैली तत्व बनाता है और इसे निर्दिष्ट दस्तावेज़ में जोड़ता है। |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStyleElement](../../aspose.svg/svgstyleelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Media](../../aspose.svg.builder/svgstyleelementbuilder/media/)(*string*) | SVG 'style' तत्व के 'media' एट्रिब्यूट को सेट करता है। यह एट्रिब्यूट उन मीडिया को निर्दिष्ट करता है जिनके लिए स्टाइल्स अभिप्रेत हैं, जिससे स्टाइल्स मीडिया प्रकार के आधार पर शर्तीय हो सकते हैं। |
| [Title](../../aspose.svg.builder/svgstyleelementbuilder/title/)(*string*) | SVG 'style' तत्व के 'title' एट्रिब्यूट को सेट करता है। यह एट्रिब्यूट स्टाइल तत्व के लिए एक सलाहकार शीर्षक प्रदान करता है, जो पहुँचयोग्यता और टूलटिप टेक्स्ट के लिए उपयोगी हो सकता है। |
| [Type](../../aspose.svg.builder/svgstyleelementbuilder/type/)(*string*) | SVG 'style' तत्व के 'type' एट्रिब्यूट को सेट करता है। यह एट्रिब्यूट तत्व की सामग्री की स्टाइल शीट भाषा को निर्दिष्ट करता है। |

### संबंधित देखें

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStyleElement](../../aspose.svg/svgstyleelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
