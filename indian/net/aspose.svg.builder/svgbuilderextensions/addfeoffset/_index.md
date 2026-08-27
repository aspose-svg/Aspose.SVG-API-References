---
title: "SVGBuilderExtensions.AddFeOffset"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddFeOffset मेथड। बिल्डर में feOffset तत्व कॉन्फ़िगरेशन जोड़ता है। यह तत्व इनपुट इमेज को निर्दिष्ट वेक्टर द्वारा ऑफ़सेट करता है"
type: docs
weight: 260
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addfeoffset/
---
## AddFeOffset<TBuilder>(*this TBuilder, Action&lt;SVGFEOffsetElementBuilder&gt;*) {#addfeoffset}

बिल्डर में एक 'feOffset' तत्व कॉन्फ़िगरेशन जोड़ता है। यह तत्व इनपुट छवि को निर्दिष्ट वेक्टर द्वारा ऑफ़सेट करता है।

```csharp
public static TBuilder AddFeOffset<TBuilder>(this TBuilder builder, 
    Action<SVGFEOffsetElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'feOffset' तत्व के लिए कॉन्फ़िगरेशन एक्शन। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGFEOffsetElementBuilder](../../svgfeoffsetelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeOffset<TBuilder>(*this TBuilder, double?, double?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEOffsetElementBuilder&gt;*) {#addfeoffset_1}

SVG बिल्डर में एक 'feOffset' तत्व जोड़ता है, जो इनपुट छवि को निर्दिष्ट वेक्टर द्वारा शिफ्ट करके ऑफ़सेट प्रभाव बनाता है।

```csharp
public static TBuilder AddFeOffset<TBuilder>(this TBuilder builder, double? dx = null, 
    double? dy = null, OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEOffsetElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | 'feOffset' तत्व को जोड़े जाने वाले SVG बिल्डर इंस्टेंस। |
| dx | क्षैतिज ऑफ़सेट दूरी। वैकल्पिक पैरामीटर। |
| dy | ऊर्ध्वाधर ऑफ़सेट दूरी। वैकल्पिक पैरामीटर। |
| in | ऑफ़सेट लागू की जाने वाली इनपुट इमेज। यह स्ट्रिंग या FilterInput हो सकती है। वैकल्पिक पैरामीटर। |
| result | इस फ़िल्टर प्रिमिटिव के लिए परिणाम पहचानकर्ता। वैकल्पिक पैरामीटर। |
| x | फ़िल्टर प्रिमिटिव उपक्षेत्र का x-निर्देशांक। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| y | फ़िल्टर प्रिमिटिव उपक्षेत्र का y-निर्देशांक। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| width | फ़िल्टर प्रिमिटिव उपक्षेत्र की चौड़ाई। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| ऊँचाई | फ़िल्टर प्रिमिटिव उपक्षेत्र की ऊँचाई। यह डबल या LengthType के साथ एक ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| भरण | तत्व के लिए भरण रंग, पेंट या पेंट सर्वर आईडी। वैकल्पिक पैरामीटर। |
| स्ट्रोक | तत्व के लिए स्ट्रोक रंग, पेंट या पेंट सर्वर आईडी। वैकल्पिक पैरामीटर। |
| id | फ़िल्टर प्रिमिटिव तत्व के लिए अद्वितीय पहचानकर्ता। वैकल्पिक पैरामीटर। |
| विस्तार | SVGFEOffsetElementBuilder को आगे कॉन्फ़िगर करने के लिए वैकल्पिक एक्शन। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEOffsetElementBuilder](../../svgfeoffsetelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
