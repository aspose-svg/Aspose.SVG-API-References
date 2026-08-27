---
title: "SVGMaskElementBuilder क्लास"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Builder.SVGMaskElementBuilder क्लास। एक SVG मास्क तत्व बनाने के लिए बिल्डर क्लास, जिसका उपयोग वर्तमान ऑब्जेक्ट को बैकग्राउंड में कंपोज़िट करने के लिए अल्फा मास्क परिभाषित करने में किया जाता है। यह क्लास मास्क तत्व के भीतर सामग्री बनाने को सक्षम करती है और SVG में मास्क तत्व के विशिष्ट विभिन्न विशेषताओं को सेट करने के लिए विधियाँ प्रदान करती है।"
type: docs
weight: 1510
url: /hi/net/aspose.svg.builder/svgmaskelementbuilder/
---
## SVGMaskElementBuilder class

SVG 'mask' तत्व बनाने के लिए Builder क्लास, जो वर्तमान ऑब्जेक्ट को बैकग्राउंड में कॉम्पोज़िट करने के लिए अल्फा मास्क को परिभाषित करने के लिए उपयोग की जाती है। यह क्लास 'mask' तत्व के भीतर सामग्री बनाने को सक्षम करती है और SVG में 'mask' तत्व के विशिष्ट विभिन्न एट्रिब्यूट सेट करने के लिए मेथड्स प्रदान करती है।

```csharp
public class SVGMaskElementBuilder : SVGElementBuilder<SVGMaskElement>, ICompositeElementBuilder, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IRectAttributeSetter
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SVGMaskElementBuilder](svgmaskelementbuilder/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMaskElement](../../aspose.svg/svgmaskelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MaskContentUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskcontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | SVG 'mask' तत्व के 'maskContentUnits' विशेषता को सेट करता है, जो मास्क की सामग्री के लिए समन्वय प्रणाली निर्दिष्ट करता है। |
| [MaskUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskunits/)(*[CoordinateUnits](../coordinateunits/)*) | SVG 'mask' तत्व के 'maskUnits' विशेषता को सेट करता है, जो मास्क की विशेषताओं के लिए समन्वय प्रणाली निर्दिष्ट करता है। |

### संबंधित देखें

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGMaskElement](../../aspose.svg/svgmaskelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../iconditionalprocessingattributesetter/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
