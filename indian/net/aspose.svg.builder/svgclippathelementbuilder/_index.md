---
title: "SVGClipPathElementBuilder क्लास"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Builder.SVGClipPathElementBuilder क्लास। एक SVG clipPath तत्व बनाने के लिए बिल्डर क्लास, जिसका उपयोग क्लिपिंग पाथ को परिभाषित करने के लिए किया जाता है। यह clipPath तत्व के भीतर सामग्री बनाने को सक्षम करता है और SVG में clipPath तत्व के विशिष्ट विभिन्न एट्रिब्यूट सेट करने के लिए मेथड प्रदान करता है।"
type: docs
weight: 1130
url: /hi/net/aspose.svg.builder/svgclippathelementbuilder/
---
## SVGClipPathElementBuilder class

SVG 'clipPath' तत्व को बनाने के लिए Builder क्लास, जिसका उपयोग क्लिपिंग पाथ को परिभाषित करने के लिए किया जाता है। यह 'clipPath' तत्व के भीतर सामग्री बनाने को सक्षम करता है और SVG में 'clipPath' तत्व के विशिष्ट विभिन्न गुण सेट करने के लिए मेथड्स प्रदान करता है।

```csharp
public class SVGClipPathElementBuilder : SVGElementBuilder<SVGClipPathElement>, 
    IAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IShapeElementBuilder
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SVGClipPathElementBuilder](svgclippathelementbuilder/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgclippathelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | clipPath तत्व में एक script तत्व जोड़ता है। |
| [AddText](../../aspose.svg.builder/svgclippathelementbuilder/addtext/)(*Action&lt;SVGTextElementBuilder&gt;*) | clipPath तत्व में एक text तत्व जोड़ता है। |
| [AddUse](../../aspose.svg.builder/svgclippathelementbuilder/adduse/)(*Action&lt;SVGUseElementBuilder&gt;*) | clipPath तत्व में एक 'use' तत्व जोड़ता है। |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGClipPathElement](../../aspose.svg/svgclippathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [ClipPathUnits](../../aspose.svg.builder/svgclippathelementbuilder/clippathunits/)(*[CoordinateUnits](../coordinateunits/)*) | SVG 'clipPath' तत्व के 'clipPathUnits' गुण को सेट करता है, जो क्लिपिंग पाथ के लिए निर्देशांक प्रणाली निर्दिष्ट करता है। |

### संबंधित देखें

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGClipPathElement](../../aspose.svg/svgclippathelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IShapeElementBuilder](../ishapeelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
