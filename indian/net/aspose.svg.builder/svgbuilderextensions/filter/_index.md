---
title: "SVGBuilderExtensions.Filter"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions Filter मेथड। कस्टम कॉन्फ़िगरेशन का उपयोग करके SVG तत्व के लिए filter एट्रिब्यूट सेट करता है।"
type: docs
weight: 840
url: /hi/net/aspose.svg.builder/svgbuilderextensions/filter/
---
## SVGBuilderExtensions.Filter<TBuilder> method

कस्टम कॉन्फ़िगरेशन का उपयोग करके SVG तत्व के लिए 'filter' विशेषता सेट करता है।

```csharp
public static TBuilder Filter<TBuilder>(this TBuilder builder, 
    Action<FilterValueListBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | FilterValueListBuilder को कॉन्फ़िगर करने के लिए एक डेलीगेट। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [FilterValueListBuilder](../../filtervaluelistbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
