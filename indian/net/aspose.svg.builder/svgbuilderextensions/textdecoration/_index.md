---
title: "SVGBuilderExtensions.TextDecoration"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions TextDecoration मेथड। टेक्स्ट में जोड़े जाने वाले सजावटी तत्वों को परिभाषित करते हुए SVG तत्व के लिए text-decoration एट्रिब्यूट सेट करता है।"
type: docs
weight: 2210
url: /hi/net/aspose.svg.builder/svgbuilderextensions/textdecoration/
---
## SVGBuilderExtensions.TextDecoration<TBuilder> method

SVG तत्व के लिए 'text-decoration' विशेषता सेट करता है, जो पाठ में जोड़ी जाने वाली सजावटों को परिभाषित करता है।

```csharp
public static TBuilder TextDecoration<TBuilder>(this TBuilder builder, bool underline = false, 
    bool overline = false, bool lineThrough = false, bool blink = false)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| अंडरलाइन | निर्दिष्ट करता है कि टेक्स्ट को अंडरलाइन किया जाना चाहिए या नहीं। |
| ओवरलाइन | निर्दिष्ट करता है कि टेक्स्ट पर ओवरलाइन होनी चाहिए या नहीं। |
| लाइनथ्रू | निर्दिष्ट करता है कि टेक्स्ट पर लाइन थ्रू होना चाहिए या नहीं। |
| ब्लिंक | निर्दिष्ट करता है कि टेक्स्ट को ब्लिंक होना चाहिए (उपयोग की अनुशंसा नहीं)। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
