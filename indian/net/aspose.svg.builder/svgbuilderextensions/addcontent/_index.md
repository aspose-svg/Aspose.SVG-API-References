---
title: "SVGBuilderExtensions.AddContent"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddContent मेथड। SVG एलिमेंट में टेक्स्ट कंटेंट जोड़ता है"
type: docs
weight: 90
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addcontent/
---
## SVGBuilderExtensions.AddContent<TBuilder> method

SVG एलिमेंट में टेक्स्ट सामग्री जोड़ता है।

```csharp
public static TBuilder AddContent<TBuilder>(this TBuilder builder, string text)
    where TBuilder : ISVGElementBuilder, ITextContentSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| text | एलिमेंट में जोड़ने के लिए टेक्स्ट। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

## टिप्पणियाँ

यह मेथड SVG एलिमेंट में सीधे टेक्स्ट कंटेंट जोड़ने की अनुमति देता है। यह उन एलिमेंट्स के लिए उपयोगी है जिनमें टेक्स्टुअल डेटा होता है।

### संबंधित देखें

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentSetter](../../itextcontentsetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
