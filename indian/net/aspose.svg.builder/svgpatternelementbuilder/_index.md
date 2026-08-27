---
title: "SVGPatternElementBuilder क्लास"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Builder.SVGPatternElementBuilder class. SVG में ग्राफ़िक तत्वों को भरने के लिए उपयोग किए जाने वाले पैटर्न को परिभाषित करने वाले SVG पैटर्न एलिमेंट को बनाने के लिए बिल्डर क्लास। यह क्लास पैटर्न एलिमेंट के विशिष्ट विभिन्न एट्रिब्यूट सेट करने और उसकी सामग्री बनाने के लिए मेथड प्रदान करती है।"
type: docs
weight: 1540
url: /hi/net/aspose.svg.builder/svgpatternelementbuilder/
---
## SVGPatternElementBuilder class

SVG 'pattern' तत्व बनाने के लिए Builder क्लास, जो SVG के भीतर ग्राफ़िक्स तत्वों को भरने के लिए उपयोग किए जाने वाले पैटर्न को परिभाषित करने के लिए उपयोग की जाती है। यह क्लास 'pattern' तत्व के विशिष्ट विभिन्न एट्रिब्यूट सेट करने के लिए मेथड्स प्रदान करती है और इसकी सामग्री बनाती है।

```csharp
public class SVGPatternElementBuilder : SVGElementBuilder<SVGPatternElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, IRectAttributeSetter, 
    IViewBoxAttributeSetter
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SVGPatternElementBuilder](svgpatternelementbuilder/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGPatternElement](../../aspose.svg/svgpatternelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgpatternelementbuilder/href/)(*string*) | SVG 'pattern' तत्व के 'href' एट्रिब्यूट को सेट करता है, जो इस पैटर्न को किसी अन्य पैटर्न का संदर्भ देता है जिससे यह एट्रिब्यूट विरासत में लेता है। |
| [PatternContentUnits](../../aspose.svg.builder/svgpatternelementbuilder/patterncontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | SVG 'pattern' तत्व के 'patternContentUnits' एट्रिब्यूट को सेट करता है, जो पैटर्न की सामग्री के लिए समन्वय प्रणाली निर्दिष्ट करता है। |
| [PatternTransform](../../aspose.svg.builder/svgpatternelementbuilder/patterntransform/)(*Func&lt;TransformBuilder, TransformBuilder&gt;*) | SVG 'pattern' तत्व के 'patternTransform' एट्रिब्यूट को सेट करता है, जो पैटर्न पर एक ट्रांसफ़ॉर्मेशन लागू करता है। |
| [PatternUnits](../../aspose.svg.builder/svgpatternelementbuilder/patternunits/)(*[CoordinateUnits](../coordinateunits/)*) | SVG 'pattern' तत्व के 'patternUnits' एट्रिब्यूट को सेट करता है, जो पैटर्न के x, y, चौड़ाई और ऊँचाई के लिए समन्वय प्रणाली निर्दिष्ट करता है। |

### संबंधित देखें

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGPatternElement](../../aspose.svg/svgpatternelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
