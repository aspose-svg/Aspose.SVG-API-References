---
title: "SVGBuilderExtensions.AddFeConvolveMatrix"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddFeConvolveMatrix मेथड। बिल्डर में एक feConvolveMatrix तत्व कॉन्फ़िगरेशन जोड़ता है। यह तत्व मैट्रिक्स कॉन्वॉल्यूशन फ़िल्टर प्रभाव लागू करता है।"
type: docs
weight: 170
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addfeconvolvematrix/
---
## AddFeConvolveMatrix<TBuilder>(*this TBuilder, Action&lt;SVGFEConvolveMatrixElementBuilder&gt;*) {#addfeconvolvematrix_1}

'feConvolveMatrix' एलिमेंट कॉन्फ़िगरेशन को बिल्डर में जोड़ता है। यह एलिमेंट मैट्रिक्स कॉन्वोल्यूशन फ़िल्टर इफ़ेक्ट लागू करता है।

```csharp
public static TBuilder AddFeConvolveMatrix<TBuilder>(this TBuilder builder, 
    Action<SVGFEConvolveMatrixElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'feConvolveMatrix' तत्व के लिए कॉन्फ़िगरेशन क्रिया। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGFEConvolveMatrixElementBuilder](../../svgfeconvolvematrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeConvolveMatrix<TBuilder>(*this TBuilder, double[], double?, double?, int?, int?, EdgeMode?, bool?, OneOf&lt;int, (int, int)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEConvolveMatrixElementBuilder&gt;*) {#addfeconvolvematrix}

'feConvolveMatrix' एलिमेंट को SVG बिल्डर में जोड़ता है, जो मैट्रिक्स कॉन्वोल्यूशन फ़िल्टर इफ़ेक्ट लागू करता है।

```csharp
public static TBuilder AddFeConvolveMatrix<TBuilder>(this TBuilder builder, 
    double[] kernelMatrix = null, double? divisor = null, double? bias = null, int? targetX = null, 
    int? targetY = null, EdgeMode? edgeMode = default, bool? preserveAlpha = null, 
    OneOf<int, (int, int)> order = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEConvolveMatrixElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | SVG बिल्डर इंस्टेंस जिसमें 'feConvolveMatrix' तत्व जोड़ा जाएगा। |
| kernelMatrix | कॉन्वॉल्यूशन के लिए मानों की मैट्रिक्स। वैकल्पिक पैरामीटर। |
| divisor | कॉन्वॉल्यूशन के लिए डिवाइज़र। वैकल्पिक पैरामीटर। |
| bias | कॉन्वॉल्यूशन के परिणाम में जोड़ा जाने वाला बायस। वैकल्पिक पैरामीटर। |
| targetX | कर्नेल मैट्रिक्स में लक्ष्य पिक्सेल का x-निर्देशांक। वैकल्पिक पैरामीटर। |
| targetY | कर्नेल मैट्रिक्स में लक्ष्य पिक्सेल का y-निर्देशांक। वैकल्पिक पैरामीटर। |
| edgeMode | कन्वॉल्यूशन में किनारे के पिक्सेल को कैसे संभालना है, यह निर्धारित करता है। वैकल्पिक पैरामीटर। |
| preserveAlpha | बताता है कि अल्फा चैनल को संरक्षित किया जाए या नहीं। वैकल्पिक पैरामीटर। |
| order | कर्नेल मैट्रिक्स का क्रम। यह एक पूर्णांक या दो पूर्णांकों के ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| in | The input for the convolution effect. Can be a string or a FilterInput. Optional parameter. |
| result | इस फ़िल्टर प्रिमिटिव के लिए परिणाम पहचानकर्ता। वैकल्पिक पैरामीटर। |
| x | फ़िल्टर प्रिमिटिव उपक्षेत्र का x-निर्देशांक। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| y | फ़िल्टर प्रिमिटिव उपक्षेत्र का y-निर्देशांक। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| width | फ़िल्टर प्रिमिटिव उपक्षेत्र की चौड़ाई। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| ऊँचाई | फ़िल्टर प्रिमिटिव उपक्षेत्र की ऊँचाई। यह डबल या LengthType के साथ एक ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| भरण | तत्व के लिए भरण रंग, पेंट या पेंट सर्वर आईडी। वैकल्पिक पैरामीटर। |
| स्ट्रोक | तत्व के लिए स्ट्रोक रंग, पेंट या पेंट सर्वर आईडी। वैकल्पिक पैरामीटर। |
| id | फ़िल्टर प्रिमिटिव तत्व के लिए अद्वितीय पहचानकर्ता। वैकल्पिक पैरामीटर। |
| विस्तार | SVGFEConvolveMatrixElementBuilder को आगे कॉन्फ़िगर करने के लिए एक वैकल्पिक क्रिया। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* enum [EdgeMode](../../edgemode/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEConvolveMatrixElementBuilder](../../svgfeconvolvematrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
