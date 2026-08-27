---
title: "SVGBuilderExtensions.AddBuilder"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddBuilder मेथड। मौजूदा SVG तत्व बिल्डर को वर्तमान SVG तत्व बिल्डर में जोड़ता है। यह मेथड पूर्वनिर्धारित SVG तत्व बिल्डर को वर्तमान बिल्डर में शामिल करने के लिए उपयोग किया जाता है।"
type: docs
weight: 60
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addbuilder/
---
## SVGBuilderExtensions.AddBuilder<TBuilder,TElementBuilder> method

एक मौजूदा SVG एलिमेंट बिल्डर को वर्तमान SVG एलिमेंट बिल्डर में जोड़ता है। यह मेथड पूर्वनिर्धारित SVG एलिमेंट बिल्डर को वर्तमान बिल्डर में शामिल करने के लिए उपयोग किया जाता है।

```csharp
public static TBuilder AddBuilder<TBuilder, TElementBuilder>(this TBuilder builder, 
    TElementBuilder elementBuilder)
    where TBuilder : ISVGElementBuilder
    where TElementBuilder : ISVGElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| TElementBuilder | कॉन्फ़िगर किए जाने वाले SVG तत्व बिल्डर का प्रकार। TElementBuilder को ISVGElementBuilder को लागू करना चाहिए। |
| बिल्डर | SVG तत्व बिल्डर जिसमें अन्य तत्व बिल्डर जोड़ा जाता है। |
| elementBuilder | जोड़ने के लिए SVG तत्व बिल्डर। |

### रिटर्न वैल्यू

मेथड चेनिंग के लिए मूल SVG तत्व बिल्डर।

### संबंधित देखें

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
