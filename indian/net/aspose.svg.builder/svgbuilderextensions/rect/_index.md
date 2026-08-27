---
title: "SVGBuilderExtensions.Rect"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions Rect मेथड। एक SVG तत्व के लिए x, y, चौड़ाई और ऊँचाई एट्रिब्यूट सेट करता है ताकि एक आयत परिभाषित हो सके।"
type: docs
weight: 1920
url: /hi/net/aspose.svg.builder/svgbuilderextensions/rect/
---
## SVGBuilderExtensions.Rect<TBuilder> method

एक SVG तत्व के लिए आयत परिभाषित करने हेतु 'x', 'y', 'width', और 'height' एट्रिब्यूट सेट करता है।

```csharp
public static TBuilder Rect<TBuilder>(this TBuilder builder, double x, double y, double width, 
    double height, LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRectAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| x | आयत का x-निर्देशांक। |
| y | आयत का y-निर्देशांक। |
| width | आयत की चौड़ाई। |
| ऊँचाई | आयत की ऊँचाई। |
| प्रकार | सभी आयामों के लिए लंबाई माप का प्रकार (डिफ़ॉल्ट पिक्सेल है)। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRectAttributeSetter](../../irectattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
