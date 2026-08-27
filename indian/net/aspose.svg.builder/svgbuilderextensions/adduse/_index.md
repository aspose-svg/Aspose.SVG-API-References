---
title: "SVGBuilderExtensions.AddUse"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddUse मेथड। बिल्डर में एक use तत्व कॉन्फ़िगरेशन जोड़ता है"
type: docs
weight: 550
url: /hi/net/aspose.svg.builder/svgbuilderextensions/adduse/
---
## AddUse<TBuilder>(*this TBuilder, Action&lt;SVGUseElementBuilder&gt;*) {#adduse}

बिल्डर में 'use' तत्व कॉन्फ़िगरेशन जोड़ता है।

```csharp
public static TBuilder AddUse<TBuilder>(this TBuilder builder, 
    Action<SVGUseElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IStructuralElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'use' तत्व के लिए कॉन्फ़िगरेशन कार्रवाई। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGUseElementBuilder](../../svguseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IStructuralElementBuilder](../../istructuralelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddUse<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGUseElementBuilder&gt;*) {#adduse_1}

SVG बिल्डर में 'use' तत्व जोड़ता है, जिससे SVG में कहीं और परिभाषित मौजूदा तत्व को पुन: उपयोग किया जा सके।

```csharp
public static TBuilder AddUse<TBuilder>(this TBuilder builder, string href = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGUseElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | 'use' तत्व को जोड़े जाने वाले SVG बिल्डर इंस्टेंस। |
| href | पुनः उपयोग किए जाने वाले मौजूदा तत्व का संदर्भ। वैकल्पिक पैरामीटर। |
| x | पुन: उपयोग किए गए तत्व का x-निर्देशांक जहाँ रखा जाता है। यह डबल या LengthType के साथ एक ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| y | पुन: उपयोग किए गए तत्व का y-निर्देशांक जहाँ रखा जाता है। यह डबल या LengthType के साथ एक ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| width | पुन: उपयोग किए गए तत्व की चौड़ाई। यह डबल या LengthType के साथ एक ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| ऊँचाई | पुन: उपयोग किए गए तत्व की ऊँचाई। यह डबल या LengthType के साथ एक ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| भरण | तत्व के लिए भरण रंग, पेंट या पेंट सर्वर आईडी। वैकल्पिक पैरामीटर। |
| स्ट्रोक | तत्व के लिए स्ट्रोक रंग, पेंट या पेंट सर्वर आईडी। वैकल्पिक पैरामीटर। |
| id | तत्व के लिए अद्वितीय पहचानकर्ता। वैकल्पिक पैरामीटर। |
| विस्तार | SVGUseElementBuilder को आगे कॉन्फ़िगर करने के लिए एक वैकल्पिक क्रिया। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGUseElementBuilder](../../svguseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
