---
title: "SVGImageElementBuilder क्लास"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Builder.SVGImageElementBuilder क्लास। SVG इमेज तत्व बनाने के लिए बिल्डर क्लास। यह तत्व SVG ग्राफ़िक्स के भीतर छवियों को एम्बेड करने के लिए उपयोग किया जाता है। यह इमेज तत्व के विशिष्ट विभिन्न एट्रिब्यूट सेट करने के लिए मेथड्स प्रदान करता है और क्लिप पाथ, मास्क, स्टाइल और स्क्रिप्ट जैसी अतिरिक्त कॉन्फ़िगरेशन जोड़ता है।"
type: docs
weight: 1470
url: /hi/net/aspose.svg.builder/svgimageelementbuilder/
---
## SVGImageElementBuilder class

SVG 'image' तत्व बनाने के लिए Builder क्लास। यह तत्व SVG ग्राफ़िक्स में इमेज एम्बेड करने के लिए उपयोग किया जाता है। यह 'image' तत्व के विशिष्ट विभिन्न एट्रिब्यूट सेट करने के लिए मेथड्स प्रदान करती है और क्लिप पाथ, मास्क, स्टाइल और स्क्रिप्ट जैसी अतिरिक्त कॉन्फ़िगरेशन जोड़ने की सुविधा देती है।

```csharp
public class SVGImageElementBuilder : SVGElementBuilder<SVGImageElement>, IAnimationElementBuilder, 
    ICompositeAttributeSetter, IDescriptiveElementBuilder, IPreserveAspectRatioAttributeSetter, 
    IRectAttributeSetter
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SVGImageElementBuilder](svgimageelementbuilder/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddClipPath](../../aspose.svg.builder/svgimageelementbuilder/addclippath/)(*Action&lt;SVGClipPathElementBuilder&gt;*) | SVG 'image' तत्व में एक क्लिप पाथ कॉन्फ़िगरेशन जोड़ता है। |
| [AddMask](../../aspose.svg.builder/svgimageelementbuilder/addmask/)(*Action&lt;SVGMaskElementBuilder&gt;*) | SVG 'image' तत्व में एक मास्क कॉन्फ़िगरेशन जोड़ता है। |
| [AddScript](../../aspose.svg.builder/svgimageelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | SVG 'image' तत्व में एक स्क्रिप्ट कॉन्फ़िगरेशन जोड़ता है। |
| [AddStyle](../../aspose.svg.builder/svgimageelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | SVG 'image' तत्व में एक स्टाइल कॉन्फ़िगरेशन जोड़ता है। |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGImageElement](../../aspose.svg/svgimageelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgimageelementbuilder/href/)(*string*) | SVG 'image' तत्व के 'href' एट्रिब्यूट को सेट करता है, एम्बेड की जाने वाली छवि का URL निर्दिष्ट करता है। |
| [HrefBase64FromBytes](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64frombytes/)(*byte[], string*) | SVG 'image' तत्व के 'href' एट्रिब्यूट को छवि के बेस64 एन्कोडेड बाइट्स का उपयोग करके सेट करता है। |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile)(*string*) | SVG 'image' तत्व के 'href' एट्रिब्यूट को बेस64 एन्कोडेड इमेज फ़ाइल का उपयोग करके सेट करता है। |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile_1)(*string, string*) | SVG 'image' तत्व के 'href' एट्रिब्यूट को निर्दिष्ट MIME प्रकार के साथ बेस64 एन्कोडेड इमेज फ़ाइल का उपयोग करके सेट करता है। |

### संबंधित देखें

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGImageElement](../../aspose.svg/svgimageelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
