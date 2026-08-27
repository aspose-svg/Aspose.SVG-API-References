---
title: "SVGBuilderExtensions.AddRect"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddRect मेथड। बिल्डर में एक rect तत्व कॉन्फ़िगरेशन जोड़ता है।"
type: docs
weight: 450
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addrect/
---
## AddRect<TBuilder>(*this TBuilder, Action&lt;SVGRectElementBuilder&gt;*) {#addrect_1}

बिल्डर में 'rect' तत्व कॉन्फ़िगरेशन जोड़ता है।

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    Action<SVGRectElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'rect' तत्व के लिए कॉन्फ़िगरेशन एक्शन। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRect<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGRectElementBuilder&gt;*) {#addrect}

SVG बिल्डर में निर्दिष्ट आयामों और शैलियों के साथ 'rect' (आयत) तत्व जोड़ता है।

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGRectElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | 'rect' तत्व को जोड़े जाने वाले SVG बिल्डर इंस्टेंस। |
| x | आयत के प्रारंभ बिंदु का x-निर्देशांक। यह डबल मान या डबल और LengthType का ट्यूपल हो सकता है। |
| y | आयत के प्रारंभ बिंदु का y-निर्देशांक। यह डबल मान या डबल और LengthType का ट्यूपल हो सकता है। |
| width | आयत की चौड़ाई। यह डबल मान या डबल और LengthType का ट्यूपल हो सकता है। |
| ऊँचाई | आयत की ऊँचाई। यह डबल मान या डबल और LengthType का ट्यूपल हो सकता है। |
| भरण | आयत के लिए भराव रंग या पेंट शैली। यह Color या Paint enum मान या पेंट सर्वर ID हो सकता है। वैकल्पिक पैरामीटर। |
| स्ट्रोक | आयत की रूपरेखा के लिए स्ट्रोक रंग या पेंट शैली। यह Color या Paint enum मान या पेंट सर्वर ID हो सकता है। वैकल्पिक पैरामीटर। |
| id | आयत तत्व के लिए अद्वितीय पहचानकर्ता। वैकल्पिक पैरामीटर। |
| विस्तार | आयत तत्व बिल्डर को आगे कॉन्फ़िगर करने के लिए वैकल्पिक एक्शन। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
