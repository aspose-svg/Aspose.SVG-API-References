---
title: "SVGBuilderExtensions.RequiredExtensions"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions RequiredExtensions मेथड। SVG तत्व पर requiredExtensions एट्रिब्यूट सेट करता है। यह एट्रिब्यूट निर्दिष्ट करता है कि SVG दस्तावेज़ फ्रैगमेंट को प्रोसेस करने के लिए कौन से एक्सटेंशन आवश्यक हैं।"
type: docs
weight: 1970
url: /hi/net/aspose.svg.builder/svgbuilderextensions/requiredextensions/
---
## SVGBuilderExtensions.RequiredExtensions<TBuilder> method

SVG तत्व पर 'requiredExtensions' एट्रिब्यूट सेट करता है। यह एट्रिब्यूट निर्दिष्ट करता है कि SVG दस्तावेज़ फ्रैगमेंट को प्रोसेस करने के लिए कौन से एक्सटेंशन आवश्यक हैं।

```csharp
public static TBuilder RequiredExtensions<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IConditionalProcessingAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर जिस पर एट्रिब्यूट सेट किया जाता है। |
| value | आवश्यक एक्सटेंशन को दर्शाने वाला स्ट्रिंग मान। |

### रिटर्न वैल्यू

मेथड चेनिंग के लिए मूल SVG तत्व बिल्डर।

### संबंधित देखें

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../../iconditionalprocessingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
