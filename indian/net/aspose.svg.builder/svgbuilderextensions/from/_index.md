---
title: "SVGBuilderExtensions.From"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions From मेथड। निर्दिष्ट लंबाई प्रकार के साथ एनीमेशन के प्रारंभिक मान को परिभाषित करने वाला from एट्रिब्यूट सेट करता है।"
type: docs
weight: 960
url: /hi/net/aspose.svg.builder/svgbuilderextensions/from/
---
## SVGBuilderExtensions.From<TBuilder> method

'from' एट्रिब्यूट सेट करता है, जो निर्दिष्ट लंबाई प्रकार के साथ एनीमेशन का प्रारंभिक मान परिभाषित करता है।

```csharp
public static TBuilder From<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| value | एनीमेशन के लिए प्रारंभिक मान। |
| प्रकार | 'from' मान के लिए लंबाई प्रकार। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
