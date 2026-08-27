---
title: "SVGBuilderExtensions.AddPath"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddPath मेथड। बिल्डर में एक path तत्व की कॉन्फ़िगरेशन जोड़ता है।"
type: docs
weight: 400
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addpath/
---
## AddPath<TBuilder>(*this TBuilder, Action&lt;SVGPathElementBuilder&gt;*) {#addpath_2}

बिल्डर में 'path' तत्व कॉन्फ़िगरेशन जोड़ता है।

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, 
    Action<SVGPathElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'path' तत्व के लिए कॉन्फ़िगरेशन एक्शन। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPath<TBuilder>(*this TBuilder, OneOf&lt;string, Action&lt;PathBuilder&gt;&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPathElementBuilder&gt;*) {#addpath}

SVG बिल्डर में 'path' तत्व जोड़ता है, जिसमें पाथ डेटा और शैलियों को निर्दिष्ट किया जाता है।

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, 
    OneOf<string, Action<PathBuilder>> d, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGPathElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | SVG बिल्डर इंस्टेंस जिसमें 'path' तत्व जोड़ा जाएगा। |
| d | एक OneOf प्रकार जो या तो पाथ डेटा को दर्शाने वाली स्ट्रिंग या PathBuilder को कॉन्फ़िगर करने वाला एक्शन हो सकता है। |
| भरण | पाथ के लिए फ़िल रंग या पेंट स्टाइल। यह Color या Paint एन्‍युम मान या पेंट सर्वर ID हो सकता है। वैकल्पिक पैरामीटर। |
| स्ट्रोक | पाथ के लिए स्ट्रोक रंग या पेंट स्टाइल। यह Color या Paint एन्‍युम मान या पेंट सर्वर ID हो सकता है। वैकल्पिक पैरामीटर। |
| id | पाथ तत्व के लिए अद्वितीय पहचानकर्ता। वैकल्पिक पैरामीटर। |
| विस्तार | पाथ तत्व बिल्डर को आगे कॉन्फ़िगर करने के लिए एक वैकल्पिक एक्शन। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* class [PathBuilder](../../pathbuilder/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPath<TBuilder>(*this TBuilder, Action&lt;PathBuilder&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPathElementBuilder&gt;*) {#addpath_1}

AddPath का ओवरलोड जो सीधे एक PathBuilder को कॉन्फ़िगर करने के लिए एक क्रिया लेता है।

```csharp
public static TBuilder AddPath<TBuilder>(this TBuilder builder, Action<PathBuilder> d, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPathElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | SVG बिल्डर इंस्टेंस जिसमें 'path' तत्व जोड़ा जाएगा। |
| d | एक एक्शन जो PathBuilder को कॉन्फ़िगर करके पाथ डेटा को परिभाषित करता है। |
| भरण | पाथ के लिए फ़िल रंग या पेंट स्टाइल। यह Color या Paint एन्‍युम मान या पेंट सर्वर ID हो सकता है। वैकल्पिक पैरामीटर। |
| स्ट्रोक | पाथ के लिए स्ट्रोक रंग या पेंट स्टाइल। यह Color या Paint एन्‍युम मान या पेंट सर्वर ID हो सकता है। वैकल्पिक पैरामीटर। |
| id | पाथ तत्व के लिए अद्वितीय पहचानकर्ता। वैकल्पिक पैरामीटर। |
| विस्तार | पाथ तत्व बिल्डर को आगे कॉन्फ़िगर करने के लिए एक वैकल्पिक एक्शन। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* class [PathBuilder](../../pathbuilder/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPathElementBuilder](../../svgpathelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
