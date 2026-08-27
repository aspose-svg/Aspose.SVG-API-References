---
title: "SVGMarkerElementBuilder क्लास"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Builder.SVGMarkerElementBuilder क्लास। SVG मार्कर तत्व को बनाने के लिए बिल्डर क्लास, जिसका उपयोग ग्राफ़िकल मार्कर जैसे तीर के सिर या बुलेट को परिभाषित करने के लिए किया जाता है, जिन्हें पाथ, लाइन, पॉलीलाइन और पॉलीगॉन तत्वों से जोड़ा जा सकता है। यह क्लास मार्कर तत्व के भीतर सामग्री बनाने को सक्षम बनाती है और SVG में मार्कर तत्व के विशिष्ट विभिन्न गुणों को सेट करने के लिए मेथड प्रदान करती है।"
type: docs
weight: 1500
url: /hi/net/aspose.svg.builder/svgmarkerelementbuilder/
---
## SVGMarkerElementBuilder class

SVG 'marker' तत्व बनाने के लिए Builder क्लास, जो ग्राफ़िकल मार्कर, जैसे एरोहेड या बुलेट, को परिभाषित करने के लिए उपयोग की जाती है, जिन्हें 'path', 'line', 'polyline' और 'polygon' तत्वों से जोड़ा जा सकता है। यह क्लास 'marker' तत्व के भीतर सामग्री बनाने को सक्षम करती है और SVG में 'marker' तत्व के विशिष्ट विभिन्न एट्रिब्यूट सेट करने के लिए मेथड्स प्रदान करती है।

```csharp
public class SVGMarkerElementBuilder : SVGElementBuilder<SVGMarkerElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, 
    IRefCoordinatesAttributeSetter, IViewBoxAttributeSetter
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SVGMarkerElementBuilder](svgmarkerelementbuilder/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMarkerElement](../../aspose.svg/svgmarkerelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MarkerHeight](../../aspose.svg.builder/svgmarkerelementbuilder/markerheight/)(*double, [LengthType](../lengthtype/)*) | SVG 'marker' तत्व के 'markerHeight' गुण को सेट करता है, जो मार्कर के व्यूपोर्ट की ऊँचाई निर्दिष्ट करता है। |
| [MarkerUnits](../../aspose.svg.builder/svgmarkerelementbuilder/markerunits/)(*[MarkerUnits](../markerunits/)*) | SVG 'marker' तत्व के 'markerUnits' गुण को सेट करता है, जो मार्कर के गुणों के लिए निर्देशांक प्रणाली निर्दिष्ट करता है। |
| [MarkerWidth](../../aspose.svg.builder/svgmarkerelementbuilder/markerwidth/)(*double, [LengthType](../lengthtype/)*) | SVG 'marker' तत्व के 'markerWidth' गुण को सेट करता है, जो मार्कर के व्यूपोर्ट की चौड़ाई निर्दिष्ट करता है। |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient)(*[Orient](../orient/)*) | SVG 'marker' तत्व के 'orient' गुण को सेट करता है, जो मार्कर की अभिविन्यास निर्दिष्ट करता है। |
| [Orient](../../aspose.svg.builder/svgmarkerelementbuilder/orient/#orient_1)(*double, [AngleUnits](../angleunits/)*) | SVG 'marker' तत्व के 'orient' गुण को सेट करता है, जो मार्कर के अभिविन्यास कोण को निर्दिष्ट करता है। |

### संबंधित देखें

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGMarkerElement](../../aspose.svg/svgmarkerelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRefCoordinatesAttributeSetter](../irefcoordinatesattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
