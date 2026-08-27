---
title: "SVGBuilderExtensions.AddMetadata"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddMetadata मेथड। बिल्डर में एक metadata तत्व कॉन्फ़िगरेशन जोड़ता है। metadata तत्व का उपयोग SVG सामग्री में मेटाडेटा जोड़ने के लिए किया जाता है।"
type: docs
weight: 390
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addmetadata/
---
## SVGBuilderExtensions.AddMetadata<TBuilder,TElement> method

बिल्डर में 'metadata' तत्व कॉन्फ़िगरेशन जोड़ता है। 'metadata' तत्व का उपयोग SVG सामग्री में मेटाडेटा जोड़ने के लिए किया जाता है।

```csharp
public static TBuilder AddMetadata<TBuilder, TElement>(this TBuilder builder, 
    Action<SVGMetadataElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IDescriptiveElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| TElement | SVG मॉडल में 'metadata' तत्व का प्रतिनिधित्व करने वाला प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'metadata' तत्व के लिए कॉन्फ़िगरेशन कार्रवाई। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGMetadataElementBuilder](../../svgmetadataelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDescriptiveElementBuilder](../../idescriptiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
