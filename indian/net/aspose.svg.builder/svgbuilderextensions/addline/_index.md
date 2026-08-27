---
title: "SVGBuilderExtensions.AddLine"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddLine मेथड। बिल्डर में एक लाइन एलिमेंट कॉन्फ़िगरेशन जोड़ता है।"
type: docs
weight: 350
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addline/
---
## AddLine<TBuilder>(*this TBuilder, Action&lt;SVGLineElementBuilder&gt;*) {#addline_1}

बिल्डर में एक 'line' तत्व कॉन्फ़िगरेशन जोड़ता है।

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    Action<SVGLineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'line' एलिमेंट के लिए कॉन्फ़िगरेशन एक्शन। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLine<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGLineElementBuilder&gt;*) {#addline}

SVG बिल्डर में एक 'line' तत्व जोड़ता है, जिसमें निर्दिष्ट प्रारंभ और अंत बिंदु तथा शैलियाँ होती हैं।

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1 = null, OneOf<double, (double, LengthType)> y1 = null, 
    OneOf<double, (double, LengthType)> x2 = null, OneOf<double, (double, LengthType)> y2 = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGLineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | SVG बिल्डर इंस्टेंस जिसमें 'line' एलिमेंट जोड़ा जाएगा। |
| x1 | लाइन के प्रारंभ बिंदु का x-कोऑर्डिनेट। यह डबल वैल्यू या डबल और LengthType के ट्यूपल में हो सकता है। |
| y1 | लाइन के प्रारंभ बिंदु का y-कोऑर्डिनेट। यह डबल वैल्यू या डबल और LengthType के ट्यूपल में हो सकता है। |
| x2 | लाइन के अंत बिंदु का x-कोऑर्डिनेट। यह डबल वैल्यू या डबल और LengthType के ट्यूपल में हो सकता है। |
| y2 | लाइन के अंत बिंदु का y-कोऑर्डिनेट। यह डबल वैल्यू या डबल और LengthType के ट्यूपल में हो सकता है। |
| भरण | लाइन के लिए फ़िल कलर या पेंट स्टाइल। यह Color या Paint एन्‍युम वैल्यू या पेंट सर्वर ID हो सकता है। वैकल्पिक पैरामीटर। |
| स्ट्रोक | लाइन के लिए स्ट्रोक कलर या पेंट स्टाइल। यह Color या Paint एन्‍युम वैल्यू या पेंट सर्वर ID हो सकता है। वैकल्पिक पैरामीटर। |
| id | लाइन एलिमेंट के लिए यूनिक आइडेंटिफ़ायर। वैकल्पिक पैरामीटर। |
| विस्तार | लाइन एलिमेंट बिल्डर को आगे कॉन्फ़िगर करने के लिए एक वैकल्पिक एक्शन। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
