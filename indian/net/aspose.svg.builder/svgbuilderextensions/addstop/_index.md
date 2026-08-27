---
title: "SVGBuilderExtensions.AddStop"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddStop method. ग्रेडिएंट स्टॉप्स को परिभाषित करने के लिए बिल्डर में एक stop एलिमेंट कॉन्फ़िगरेशन जोड़ता है।"
type: docs
weight: 480
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addstop/
---
## AddStop<TBuilder>(*this TBuilder, Action&lt;SVGStopElementBuilder&gt;*) {#addstop}

ग्रेडिएंट स्टॉप्स को परिभाषित करने के लिए बिल्डर में 'stop' तत्व कॉन्फ़िगरेशन जोड़ता है।

```csharp
public static TBuilder AddStop<TBuilder>(this TBuilder builder, 
    Action<SVGStopElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'stop' एलिमेंट के लिए कॉन्फ़िगरेशन एक्शन। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGStopElementBuilder](../../svgstopelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddStop<TBuilder>(*this TBuilder, Color?, double?, OneOf&lt;double, (double, StopUnitType)&gt;, string, Action&lt;SVGStopElementBuilder&gt;*) {#addstop_1}

SVG बिल्डर में ग्रेडिएंट में 'stop' तत्व जोड़ता है, जिसमें किसी विशेष ऑफ़सेट पर रंग और अपारदर्शिता को निर्दिष्ट किया जाता है।

```csharp
public static TBuilder AddStop<TBuilder>(this TBuilder builder, Color? stopColor = default, 
    double? stopOpacity = null, OneOf<double, (double, StopUnitType)> offset = null, 
    string id = null, Action<SVGStopElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IGradientStopElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | 'stop' एलिमेंट जोड़े जाने वाला SVG बिल्डर इंस्टेंस। |
| stopColor | स्टॉप पर रंग। वैकल्पिक पैरामीटर। |
| stopOpacity | स्टॉप पर अपारदर्शिता। वैकल्पिक पैरामीटर। |
| offset | ग्रेडिएंट के भीतर स्टॉप का ऑफ़सेट। यह डबल या StopUnitType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| id | स्टॉप एलिमेंट के लिए अद्वितीय पहचानकर्ता। वैकल्पिक पैरामीटर। |
| विस्तार | स्टॉप एलिमेंट बिल्डर को आगे कॉन्फ़िगर करने के लिए वैकल्पिक एक्शन। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [StopUnitType](../../stopunittype/)
* class [SVGStopElementBuilder](../../svgstopelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGradientStopElementBuilder](../../igradientstopelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
