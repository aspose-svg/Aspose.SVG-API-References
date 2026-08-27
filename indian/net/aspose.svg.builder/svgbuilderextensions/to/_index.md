---
title: "SVGBuilderExtensions.To"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions To method. निर्दिष्ट लंबाई प्रकार के साथ एनीमेशन के समाप्ति मान को परिभाषित करने वाले to विशेषता को सेट करता है।"
type: docs
weight: 2250
url: /hi/net/aspose.svg.builder/svgbuilderextensions/to/
---
## SVGBuilderExtensions.To<TBuilder> method

'to' विशेषता सेट करता है, जो निर्दिष्ट लंबाई प्रकार के साथ एनीमेशन के समाप्ति मान को परिभाषित करता है।

```csharp
public static TBuilder To<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| value | एनीमेशन के समाप्ति मान। |
| प्रकार | 'to' मान के लिए लंबाई प्रकार। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
