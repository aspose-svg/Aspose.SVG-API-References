---
title: "SVGBuilderExtensions.AddDesc"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddDesc method. बिल्डर में एक desc तत्व कॉन्फ़िगरेशन जोड़ता है। desc तत्व SVG सामग्री के लिए विवरण प्रदान करने के लिए उपयोग किया जाता है।"
type: docs
weight: 110
url: /hi/net/aspose.svg.builder/svgbuilderextensions/adddesc/
---
## SVGBuilderExtensions.AddDesc<TBuilder> method

'desc' एलिमेंट कॉन्फ़िगरेशन को बिल्डर में जोड़ता है। 'desc' एलिमेंट का उपयोग SVG सामग्री के लिए विवरण प्रदान करने के लिए किया जाता है।

```csharp
public static TBuilder AddDesc<TBuilder>(this TBuilder builder, 
    Action<SVGDescElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'desc' तत्व के लिए कॉन्फ़िगरेशन कार्रवाई। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGDescElementBuilder](../../svgdescelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
