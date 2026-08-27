---
title: "SVGBuilderExtensions.AddPolyline"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddPolyline मेथड। बिल्डर में एक polyline एलिमेंट कॉन्फ़िगरेशन जोड़ता है"
type: docs
weight: 430
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addpolyline/
---
## AddPolyline<TBuilder>(*this TBuilder, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline_1}

बिल्डर में 'polyline' तत्व कॉन्फ़िगरेशन जोड़ता है।

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, 
    Action<SVGPolylineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'polyline' एलिमेंट के लिए कॉन्फ़िगरेशन एक्शन। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolyline<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline}

SVG बिल्डर में 'polyline' तत्व जोड़ता है, जिसमें इसके शीर्ष बिंदु और शैलियों को निर्दिष्ट किया जाता है।

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolylineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | 'polyline' एलिमेंट को जोड़ा जाएगा, वह SVG बिल्डर इंस्टेंस। |
| points | डबल्स की एक एरे जो polyline के पॉइंट्स को दर्शाती है (x और y निर्देशांक वैकल्पिक रूप से)। |
| भरण | polyline के लिए फ़िल रंग या पेंट स्टाइल। यह Color या Paint enum मान या पेंट सर्वर ID हो सकता है। वैकल्पिक पैरामीटर। |
| स्ट्रोक | polyline के लिए स्ट्रोक रंग या पेंट स्टाइल। यह Color या Paint enum मान या पेंट सर्वर ID हो सकता है। वैकल्पिक पैरामीटर। |
| id | polyline एलिमेंट के लिए अद्वितीय पहचानकर्ता। वैकल्पिक पैरामीटर। |
| विस्तार | polyline एलिमेंट बिल्डर को आगे कॉन्फ़िगर करने के लिए वैकल्पिक एक्शन। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
