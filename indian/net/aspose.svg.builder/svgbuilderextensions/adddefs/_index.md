---
title: "SVGBuilderExtensions.AddDefs"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddDefs method. बिल्डर में एक defs परिभाषा तत्व कॉन्फ़िगरेशन जोड़ता है।"
type: docs
weight: 100
url: /hi/net/aspose.svg.builder/svgbuilderextensions/adddefs/
---
## SVGBuilderExtensions.AddDefs<TBuilder> method

'defs' (परिभाषाएँ) एलिमेंट कॉन्फ़िगरेशन को बिल्डर में जोड़ता है।

```csharp
public static TBuilder AddDefs<TBuilder>(this TBuilder builder, 
    Action<SVGDefsElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'defs' तत्व के लिए कॉन्फ़िगरेशन कार्रवाई। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGDefsElementBuilder](../../svgdefselementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
