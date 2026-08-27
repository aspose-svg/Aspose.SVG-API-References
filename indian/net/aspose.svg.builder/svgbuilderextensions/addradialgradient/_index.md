---
title: "SVGBuilderExtensions.AddRadialGradient"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddRadialGradient मेथड। बिल्डर में radialGradient तत्व की कॉन्फ़िगरेशन जोड़ता है।"
type: docs
weight: 440
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addradialgradient/
---
## AddRadialGradient<TBuilder>(*this TBuilder, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient_1}

बिल्डर में 'radialGradient' तत्व कॉन्फ़िगरेशन जोड़ता है।

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    Action<SVGRadialGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'radialGradient' तत्व के लिए कॉन्फ़िगरेशन एक्शन। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRadialGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient}

SVG बिल्डर में 'radialGradient' तत्व जोड़ता है, जिसमें इसका केंद्र, त्रिज्या, फोकल पॉइंट्स और अन्य ग्रेडिएंट गुणों को निर्दिष्ट किया जाता है।

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<double, (double, LengthType)> fx = null, 
    OneOf<double, (double, LengthType)> fy = null, CoordinateUnits? gradientUnits = default, 
    SpreadMethod? spreadMethod = default, string href = null, string id = null, 
    Action<SVGRadialGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | 'radialGradient' तत्व जोड़े जाने वाला SVG बिल्डर इंस्टेंस। |
| cx | ग्रेडिएंट के केंद्र का x-कोऑर्डिनेट। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| cy | ग्रेडिएंट के केंद्र का y-कोऑर्डिनेट। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| r | ग्रेडिएंट की त्रिज्या। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| fx | ग्रेडिएंट के फोकल पॉइंट का x-कोऑर्डिनेट। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| fy | ग्रेडिएंट के फोकल पॉइंट का y-कोऑर्डिनेट। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| gradientUnits | ग्रेडिएंट के लिए कोऑर्डिनेट सिस्टम निर्दिष्ट करता है। वैकल्पिक पैरामीटर। |
| spreadMethod | ग्रेडिएंट के प्रारंभ और अंत बिंदुओं से परे कैसे फैलता है, यह परिभाषित करता है। वैकल्पिक पैरामीटर। |
| href | यदि लागू हो, तो किसी अन्य ग्रेडिएंट का संदर्भ। वैकल्पिक पैरामीटर। |
| id | ग्रेडिएंट तत्व के लिए अद्वितीय पहचानकर्ता। वैकल्पिक पैरामीटर। |
| विस्तार | रेडियल ग्रेडिएंट तत्व बिल्डर को आगे कॉन्फ़िगर करने के लिए एक वैकल्पिक कार्रवाई। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
