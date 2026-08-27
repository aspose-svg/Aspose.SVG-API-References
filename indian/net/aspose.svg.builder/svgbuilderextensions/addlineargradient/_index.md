---
title: "SVGBuilderExtensions.AddLinearGradient"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddLinearGradient मेथड। बिल्डर में linearGradient तत्व की कॉन्फ़िगरेशन जोड़ता है।"
type: docs
weight: 360
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addlineargradient/
---
## AddLinearGradient<TBuilder>(*this TBuilder, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient_1}

बिल्डर में 'linearGradient' तत्व कॉन्फ़िगरेशन जोड़ता है।

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    Action<SVGLinearGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'linearGradient' तत्व के लिए कॉन्फ़िगरेशन एक्शन। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLinearGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient}

SVG बिल्डर में 'linearGradient' तत्व जोड़ता है, जिसमें इसकी प्रारंभ और समाप्ति स्थितियों तथा अन्य ग्रेडिएंट गुणों को निर्दिष्ट किया जाता है।

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1, OneOf<double, (double, LengthType)> y1, 
    OneOf<double, (double, LengthType)> x2, OneOf<double, (double, LengthType)> y2, 
    CoordinateUnits? gradientUnits, SpreadMethod? spreadMethod, string href = null, 
    string id = null, Action<SVGLinearGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | 'linearGradient' तत्व को जोड़ा जाएगा, उस SVG बिल्डर इंस्टेंस के लिए। |
| x1 | ग्रेडिएंट के लिए प्रारंभिक x-कोऑर्डिनेट। यह डबल या LengthType के साथ ValueTuple हो सकता है। |
| y1 | ग्रेडिएंट के लिए प्रारंभिक y-कोऑर्डिनेट। यह डबल या LengthType के साथ ValueTuple हो सकता है। |
| x2 | ग्रेडिएंट के लिए समाप्ति x-कोऑर्डिनेट। यह डबल या LengthType के साथ ValueTuple हो सकता है। |
| y2 | ग्रेडिएंट के लिए समाप्ति y-कोऑर्डिनेट। यह डबल या LengthType के साथ ValueTuple हो सकता है। |
| gradientUnits | ग्रेडिएंट के लिए कोऑर्डिनेट सिस्टम निर्दिष्ट करता है। वैकल्पिक पैरामीटर। |
| spreadMethod | ग्रेडिएंट के प्रारंभ और अंत बिंदुओं से परे कैसे फैलता है, यह परिभाषित करता है। वैकल्पिक पैरामीटर। |
| href | यदि लागू हो, तो किसी अन्य ग्रेडिएंट का संदर्भ। वैकल्पिक पैरामीटर। |
| id | ग्रेडिएंट तत्व के लिए अद्वितीय पहचानकर्ता। वैकल्पिक पैरामीटर। |
| विस्तार | linear gradient तत्व बिल्डर को आगे कॉन्फ़िगर करने के लिए वैकल्पिक एक्शन। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
