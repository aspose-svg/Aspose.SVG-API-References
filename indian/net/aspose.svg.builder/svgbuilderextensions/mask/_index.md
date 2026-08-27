---
title: "SVGBuilderExtensions.Mask"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions Mask मेथड। कस्टम मास्क कॉन्फ़िगरेशन का उपयोग करके SVG एलिमेंट के लिए mask एट्रिब्यूट सेट करता है"
type: docs
weight: 1150
url: /hi/net/aspose.svg.builder/svgbuilderextensions/mask/
---
## SVGBuilderExtensions.Mask<TBuilder> method

कस्टम मास्क कॉन्फ़िगरेशन का उपयोग करके SVG तत्व के लिए 'mask' विशेषता सेट करता है।

```csharp
public static TBuilder Mask<TBuilder>(this TBuilder builder, Action<MaskBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | मास्क को कॉन्फ़िगर करने के लिए एक डेलीगेट। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [MaskBuilder](../../maskbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
