---
title: "SVGBuilderExtensions.AddImage"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddImage मेथड। बिल्डर में एक इमेज एलिमेंट कॉन्फ़िगरेशन जोड़ता है।"
type: docs
weight: 330
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addimage/
---
## AddImage<TBuilder>(*this TBuilder, Action&lt;SVGImageElementBuilder&gt;*) {#addimage}

बिल्डर में एक 'image' तत्व कॉन्फ़िगरेशन जोड़ता है।

```csharp
public static TBuilder AddImage<TBuilder>(this TBuilder builder, 
    Action<SVGImageElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'image' एलिमेंट के लिए कॉन्फ़िगरेशन एक्शन। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGImageElementBuilder](../../svgimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddImage<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, string, Action&lt;SVGImageElementBuilder&gt;*) {#addimage_1}

SVG बिल्डर में एक 'image' तत्व जोड़ता है, जो एक बाहरी छवि को SVG दस्तावेज़ में एम्बेड करता है।

```csharp
public static TBuilder AddImage<TBuilder>(this TBuilder builder, string href = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, string id = null, 
    Action<SVGImageElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | 'image' एलिमेंट को जोड़ने के लिए SVG बिल्डर इंस्टेंस। |
| href | बाहरी इमेज का URL या रेफ़रेंस। वैकल्पिक पैरामीटर। |
| x | इमेज जहाँ रखी जाती है उसका x-कोऑर्डिनेट। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| y | इमेज जहाँ रखी जाती है उसका y-कोऑर्डिनेट। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| width | इमेज की चौड़ाई। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| ऊँचाई | इमेज की ऊँचाई। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| id | इमेज एलिमेंट के लिए यूनिक आइडेंटिफायर। वैकल्पिक पैरामीटर। |
| विस्तार | SVGImageElementBuilder को आगे कॉन्फ़िगर करने के लिए एक वैकल्पिक एक्शन। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [SVGImageElementBuilder](../../svgimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
