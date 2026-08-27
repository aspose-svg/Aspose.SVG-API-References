---
title: "SVGBuilderExtensions.Transform"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions Transform मेथड। SVG तत्व के लिए transform एट्रिब्यूट सेट करता है।"
type: docs
weight: 2260
url: /hi/net/aspose.svg.builder/svgbuilderextensions/transform/
---
## SVGBuilderExtensions.Transform<TBuilder> method

SVG तत्व के लिए 'transform' विशेषता सेट करता है।

```csharp
public static TBuilder Transform<TBuilder>(this TBuilder builder, 
    Func<TransformBuilder, TransformBuilder> configure)
    where TBuilder : ISVGElementBuilder, ITransformAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | SVG ट्रांसफ़ॉर्म को कॉन्फ़िगर करने के लिए एक फ़ंक्शन। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [TransformBuilder](../../transformbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITransformAttributeSetter](../../itransformattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
