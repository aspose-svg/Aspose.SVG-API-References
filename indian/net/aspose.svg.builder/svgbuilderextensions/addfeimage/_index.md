---
title: "SVGBuilderExtensions.AddFeImage"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddFeImage मेथड। बिल्डर में एक feImage तत्व कॉन्फ़िगरेशन जोड़ता है। यह तत्व बाहरी छवि को प्राप्त करता है और फ़िल्टर पाइपलाइन में शामिल करता है।"
type: docs
weight: 230
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addfeimage/
---
## AddFeImage<TBuilder>(*this TBuilder, Action&lt;SVGFEImageElementBuilder&gt;*) {#addfeimage}

बिल्डर में एक 'feImage' तत्व कॉन्फ़िगरेशन जोड़ता है। यह तत्व एक बाहरी छवि को प्राप्त करता है और उसे फ़िल्टर पाइपलाइन में शामिल करता है।

```csharp
public static TBuilder AddFeImage<TBuilder>(this TBuilder builder, 
    Action<SVGFEImageElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'feImage' तत्व के लिए कॉन्फ़िगरेशन क्रिया। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGFEImageElementBuilder](../../svgfeimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeImage<TBuilder>(*this TBuilder, string, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEImageElementBuilder&gt;*) {#addfeimage_1}

SVG बिल्डर में एक 'feImage' तत्व जोड़ता है, जो एक बाहरी छवि को फ़िल्टर प्रभाव में सम्मिलित करता है।

```csharp
public static TBuilder AddFeImage<TBuilder>(this TBuilder builder, string href = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEImageElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | 'feImage' तत्व को जोड़े जाने वाले SVG बिल्डर इंस्टेंस। |
| href | बाहरी इमेज का URL या रेफ़रेंस। वैकल्पिक पैरामीटर। |
| result | इस फ़िल्टर प्रिमिटिव के लिए परिणाम पहचानकर्ता। वैकल्पिक पैरामीटर। |
| x | फ़िल्टर प्रिमिटिव उपक्षेत्र का x-निर्देशांक। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| y | फ़िल्टर प्रिमिटिव उपक्षेत्र का y-निर्देशांक। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| width | फ़िल्टर प्रिमिटिव उपक्षेत्र की चौड़ाई। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| ऊँचाई | फ़िल्टर प्रिमिटिव उपक्षेत्र की ऊँचाई। यह डबल या LengthType के साथ एक ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| भरण | तत्व के लिए भरण रंग, पेंट या पेंट सर्वर आईडी। वैकल्पिक पैरामीटर। |
| स्ट्रोक | तत्व के लिए स्ट्रोक रंग, पेंट या पेंट सर्वर आईडी। वैकल्पिक पैरामीटर। |
| id | फ़िल्टर प्रिमिटिव तत्व के लिए अद्वितीय पहचानकर्ता। वैकल्पिक पैरामीटर। |
| विस्तार | SVGFEImageElementBuilder को आगे कॉन्फ़िगर करने के लिए एक वैकल्पिक क्रिया। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEImageElementBuilder](../../svgfeimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
