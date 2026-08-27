---
title: "SVGBuilderExtensions.ViewBox"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions ViewBox मेथड। एक SVG एलिमेंट के लिए viewBox एट्रिब्यूट सेट करता है।"
type: docs
weight: 2300
url: /hi/net/aspose.svg.builder/svgbuilderextensions/viewbox/
---
## SVGBuilderExtensions.ViewBox<TBuilder> method

SVG तत्व के लिए 'viewBox' विशेषता सेट करता है।

```csharp
public static TBuilder ViewBox<TBuilder>(this TBuilder builder, double minX, double minY, 
    double width, double height)
    where TBuilder : ISVGElementBuilder, IViewBoxAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| minX | viewBox का न्यूनतम X निर्देशांक। |
| minY | viewBox का न्यूनतम Y निर्देशांक। |
| width | viewBox की चौड़ाई। |
| ऊँचाई | viewBox की ऊँचाई। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IViewBoxAttributeSetter](../../iviewboxattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
