---
title: "SVGBuilderExtensions.By"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions By विधि. सेट करता है by एट्रिब्यूट को जो एनीमेशन के लिए निर्दिष्ट लंबाई प्रकार के साथ सापेक्ष ऑफसेट मान को परिभाषित करता है"
type: docs
weight: 620
url: /hi/net/aspose.svg.builder/svgbuilderextensions/by/
---
## SVGBuilderExtensions.By<TBuilder> method

'by' गुण सेट करता है, जो निर्दिष्ट लंबाई प्रकार के साथ एनीमेशन के सापेक्ष ऑफ़सेट मान को परिभाषित करता है।

```csharp
public static TBuilder By<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| value | एनीमेशन के लिए सापेक्ष ऑफसेट मान। |
| प्रकार | 'by' मान के लिए लंबाई प्रकार। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
