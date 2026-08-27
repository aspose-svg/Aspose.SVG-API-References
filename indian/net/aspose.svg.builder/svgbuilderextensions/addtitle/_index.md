---
title: "SVGBuilderExtensions.AddTitle"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddTitle मेथड। बिल्डर में टाइटल एलिमेंट कॉन्फ़िगरेशन जोड़ता है। टाइटल एलिमेंट SVG सामग्री के लिए शीर्षक प्रदान करने हेतु उपयोग किया जाता है।"
type: docs
weight: 540
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addtitle/
---
## SVGBuilderExtensions.AddTitle<TBuilder> method

बिल्डर में 'title' तत्व कॉन्फ़िगरेशन जोड़ता है। 'title' तत्व का उपयोग SVG सामग्री के लिए शीर्षक प्रदान करने के लिए किया जाता है।

```csharp
public static TBuilder AddTitle<TBuilder>(this TBuilder builder, 
    Action<SVGTitleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'title' तत्व के लिए कॉन्फ़िगरेशन क्रिया। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGTitleElementBuilder](../../svgtitleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
