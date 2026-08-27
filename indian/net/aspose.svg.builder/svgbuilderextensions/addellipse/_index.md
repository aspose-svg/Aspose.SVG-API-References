---
title: "SVGBuilderExtensions.AddEllipse"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddEllipse मेथड। बिल्डर में एक ellipse तत्व कॉन्फ़िगरेशन जोड़ता है।"
type: docs
weight: 120
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addellipse/
---
## AddEllipse<TBuilder>(*this TBuilder, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse_1}

'ellipse' एलिमेंट कॉन्फ़िगरेशन को बिल्डर में जोड़ता है।

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    Action<SVGEllipseElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'ellipse' तत्व के लिए कॉन्फ़िगरेशन एक्शन। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddEllipse<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse}

'ellipse' एलिमेंट को SVG बिल्डर में जोड़ता है, जिसमें इसका केंद्र, त्रिज्याएँ और शैलियाँ निर्दिष्ट की गई हैं।

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> rx = null, OneOf<double, (double, LengthType)> ry = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGEllipseElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | 'ellipse' तत्व को जोड़ने के लिए SVG बिल्डर इंस्टेंस। |
| cx | ellipse के केंद्र का x-निर्देशांक। यह डबल मान या डबल और LengthType का ट्यूपल हो सकता है। |
| cy | ellipse के केंद्र का y-निर्देशांक। यह डबल मान या डबल और LengthType का ट्यूपल हो सकता है। |
| rx | ellipse का x-रेडियस। यह डबल मान या डबल और LengthType का ट्यूपल हो सकता है। |
| ry | ellipse का y-रेडियस। यह डबल मान या डबल और LengthType का ट्यूपल हो सकता है। |
| भरण | ellipse के लिए fill रंग या पेंट स्टाइल। यह Color या Paint enum मान या पेंट सर्वर ID हो सकता है। वैकल्पिक पैरामीटर। |
| स्ट्रोक | ellipse के लिए stroke रंग या पेंट स्टाइल। यह Color या Paint enum मान या पेंट सर्वर ID हो सकता है। वैकल्पिक पैरामीटर। |
| id | ellipse तत्व के लिए अद्वितीय पहचानकर्ता। वैकल्पिक पैरामीटर। |
| विस्तार | ellipse तत्व बिल्डर को आगे कॉन्फ़िगर करने के लिए एक वैकल्पिक एक्शन। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
