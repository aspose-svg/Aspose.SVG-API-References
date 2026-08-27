---
title: "SVGBuilderExtensions.FillOpacity"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions FillOpacity मेथड। SVG तत्व के लिए fill-opacity एट्रिब्यूट सेट करता है। मान 0.0 (पूरी तरह पारदर्शी) से 1.0 (पूरी तरह अपारदर्शी) के बीच होना चाहिए।"
type: docs
weight: 820
url: /hi/net/aspose.svg.builder/svgbuilderextensions/fillopacity/
---
## SVGBuilderExtensions.FillOpacity<TBuilder> method

SVG तत्व के लिए 'fill-opacity' विशेषता सेट करता है। मान 0.0 (पूरी तरह पारदर्शी) और 1.0 (पूरी तरह अपारदर्शी) के बीच होना चाहिए।

```csharp
public static TBuilder FillOpacity<TBuilder>(this TBuilder builder, double opacity)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| opacity | सेट करने के लिए opacity मान। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | यदि opacity वैध सीमा में नहीं है तो थ्रो किया जाता है। |

### संबंधित देखें

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
