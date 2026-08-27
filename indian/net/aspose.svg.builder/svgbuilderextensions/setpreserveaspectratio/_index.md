---
title: "SVGBuilderExtensions.SetPreserveAspectRatio"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions SetPreserveAspectRatio मेथड। SVG एलिमेंट के लिए preserveAspectRatio एट्रिब्यूट सेट करता है।"
type: docs
weight: 2020
url: /hi/net/aspose.svg.builder/svgbuilderextensions/setpreserveaspectratio/
---
## SVGBuilderExtensions.SetPreserveAspectRatio<TBuilder> method

SVG तत्व के लिए 'preserveAspectRatio' विशेषता निर्धारित करता है।

```csharp
public static TBuilder SetPreserveAspectRatio<TBuilder>(this TBuilder builder, 
    AspectRatioAlign align, AspectRatioScaling meetOrSlice = AspectRatioScaling.Meet)
    where TBuilder : ISVGElementBuilder, IPreserveAspectRatioAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| align | अस्पेक्ट रेशियो के लिए संरेखण सेटिंग। |
| meetOrSlice | निर्दिष्ट करता है कि अस्पेक्ट रेशियो कैसे संरक्षित किया जाता है (डिफ़ॉल्ट 'Meet' है)। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* enum [AspectRatioAlign](../../aspectratioalign/)
* enum [AspectRatioScaling](../../aspectratioscaling/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../../ipreserveaspectratioattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
