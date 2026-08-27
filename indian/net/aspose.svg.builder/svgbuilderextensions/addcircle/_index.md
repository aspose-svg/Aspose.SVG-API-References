---
title: "SVGBuilderExtensions.AddCircle"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddCircle मेथड। बिल्डर में एक सर्कल एलिमेंट कॉन्फ़िगरेशन जोड़ता है।"
type: docs
weight: 70
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addcircle/
---
## AddCircle<TBuilder>(*this TBuilder, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle_1}

'circle' एलिमेंट कॉन्फ़िगरेशन को बिल्डर में जोड़ता है।

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    Action<SVGCircleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'circle' एलिमेंट के लिए कॉन्फ़िगरेशन कार्रवाई। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddCircle<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle}

निर्दिष्ट केंद्र, त्रिज्या और शैलियों के साथ 'circle' एलिमेंट को SVG बिल्डर में जोड़ता है।

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGCircleElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | 'circle' एलिमेंट को जोड़े जाने वाला SVG बिल्डर इंस्टेंस। |
| cx | सर्कल के केंद्र का x-निर्देशांक। यह डबल मान या डबल और LengthType का ट्यूपल हो सकता है। |
| cy | सर्कल के केंद्र का y-निर्देशांक। यह डबल मान या डबल और LengthType का ट्यूपल हो सकता है। |
| r | सर्कल की त्रिज्या। यह डबल मान या डबल और LengthType का ट्यूपल हो सकता है। |
| भरण | सर्कल के लिए फ़िल रंग या पेंट शैली। यह Color या Paint एन्‍युम मान या पेंट सर्वर ID हो सकता है। वैकल्पिक पैरामीटर। |
| स्ट्रोक | सर्कल की रूपरेखा के लिए स्ट्रोक रंग या पेंट शैली। यह Color या Paint एन्‍युम मान या पेंट सर्वर ID हो सकता है। वैकल्पिक पैरामीटर। |
| id | सर्कल एलिमेंट के लिए अद्वितीय पहचानकर्ता। वैकल्पिक पैरामीटर। |
| विस्तार | सर्कल एलिमेंट बिल्डर को आगे कॉन्फ़िगर करने के लिए वैकल्पिक कार्रवाई। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
