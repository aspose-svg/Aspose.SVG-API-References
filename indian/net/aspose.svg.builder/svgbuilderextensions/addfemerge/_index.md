---
title: "SVGBuilderExtensions.AddFeMerge"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddFeMerge मेथड। बिल्डर में एक feMerge एलिमेंट कॉन्फ़िगरेशन जोड़ता है। यह एलिमेंट फ़िल्टर इफ़ेक्ट्स को क्रमिक रूप से नहीं बल्कि एक साथ लागू करने की अनुमति देता है"
type: docs
weight: 240
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addfemerge/
---
## SVGBuilderExtensions.AddFeMerge<TBuilder> method

बिल्डर में एक 'feMerge' तत्व कॉन्फ़िगरेशन जोड़ता है। यह तत्व फ़िल्टर प्रभावों को क्रमिक रूप से नहीं, बल्कि एक साथ लागू करने की अनुमति देता है।

```csharp
public static TBuilder AddFeMerge<TBuilder>(this TBuilder builder, 
    Action<SVGFEMergeElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | ‘feMerge’ तत्व के लिए कॉन्फ़िगरेशन क्रिया। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGFEMergeElementBuilder](../../svgfemergeelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
