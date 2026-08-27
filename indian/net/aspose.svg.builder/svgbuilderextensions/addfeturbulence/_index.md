---
title: "SVGBuilderExtensions.AddFeTurbulence"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddFeTurbulence मेथड। बिल्डर में एक feTurbulence तत्व कॉन्फ़िगरेशन जोड़ता है। यह तत्व पर्लिन शोर का उपयोग करके एक छवि बनाता है, जो बादल या संगमरमर जैसी बनावट बनाने के लिए उपयोगी है।"
type: docs
weight: 290
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addfeturbulence/
---
## AddFeTurbulence<TBuilder>(*this TBuilder, Action&lt;SVGFETurbulenceElementBuilder&gt;*) {#addfeturbulence_1}

बिल्डर में एक 'feTurbulence' तत्व कॉन्फ़िगरेशन जोड़ता है। यह तत्व पर्लिन शोर का उपयोग करके एक छवि बनाता है, जो बादल या संगमरमर जैसी बनावट बनाने में उपयोगी है।

```csharp
public static TBuilder AddFeTurbulence<TBuilder>(this TBuilder builder, 
    Action<SVGFETurbulenceElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'feTurbulence' तत्व के लिए कॉन्फ़िगरेशन कार्रवाई। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGFETurbulenceElementBuilder](../../svgfeturbulenceelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeTurbulence<TBuilder>(*this TBuilder, OneOf&lt;double, (double, double)&gt;, int?, double?, StitchTiles?, TurbulenceType?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFETurbulenceElementBuilder&gt;*) {#addfeturbulence}

SVG बिल्डर में एक 'feTurbulence' तत्व जोड़ता है, जो पर्लिन शोर का उपयोग करके बादल या संगमरमर जैसी टर्बुलेंस प्रभाव बनाता है।

```csharp
public static TBuilder AddFeTurbulence<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, double)> baseFrequency = null, int? numOctaves = null, 
    double? seed = null, StitchTiles? stitchTiles = default, TurbulenceType? type = default, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFETurbulenceElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | 'feTurbulence' तत्व जोड़ा जाएगा, उस SVG बिल्डर इंस्टेंस के लिए। |
| baseFrequency | टर्ब्युलेंस की बेस फ़्रीक्वेंसी। यह एक डबल या दो डबल्स का ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| numOctaves | टर्ब्युलेंस के लिए ऑक्टेव्स की संख्या। वैकल्पिक पैरामीटर। |
| seed | रैंडम नंबर जेनरेटर के लिए सीड नंबर। वैकल्पिक पैरामीटर। |
| stitchTiles | निर्देशित करता है कि टाइल्स एक साथ सिलाई गई हैं या नहीं। वैकल्पिक पैरामीटर। |
| प्रकार | टर्ब्युलेंस का प्रकार (फ्रैक्टल नॉइज़ या टर्ब्युलेंस)। वैकल्पिक पैरामीटर। |
| in | इनपुट इमेज जिस पर टर्ब्युलेंस प्रभाव लागू होगा। यह एक स्ट्रिंग या FilterInput हो सकता है। वैकल्पिक पैरामीटर। |
| result | इस फ़िल्टर प्रिमिटिव के लिए परिणाम पहचानकर्ता। वैकल्पिक पैरामीटर। |
| x | फ़िल्टर प्रिमिटिव उपक्षेत्र का x-निर्देशांक। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| y | फ़िल्टर प्रिमिटिव उपक्षेत्र का y-निर्देशांक। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| width | फ़िल्टर प्रिमिटिव उपक्षेत्र की चौड़ाई। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| ऊँचाई | फ़िल्टर प्रिमिटिव उपक्षेत्र की ऊँचाई। यह डबल या LengthType के साथ एक ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| भरण | तत्व के लिए भरण रंग, पेंट या पेंट सर्वर आईडी। वैकल्पिक पैरामीटर। |
| स्ट्रोक | तत्व के लिए स्ट्रोक रंग, पेंट या पेंट सर्वर आईडी। वैकल्पिक पैरामीटर। |
| id | फ़िल्टर प्रिमिटिव तत्व के लिए अद्वितीय पहचानकर्ता। वैकल्पिक पैरामीटर। |
| विस्तार | SVGFETurbulenceElementBuilder को आगे कॉन्फ़िगर करने के लिए एक वैकल्पिक एक्शन। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [StitchTiles](../../stitchtiles/)
* enum [TurbulenceType](../../turbulencetype/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFETurbulenceElementBuilder](../../svgfeturbulenceelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
