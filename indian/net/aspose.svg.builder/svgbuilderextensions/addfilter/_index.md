---
title: "SVGBuilderExtensions.AddFilter"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddFilter मेथड। बिल्डर में एक फ़िल्टर एलिमेंट कॉन्फ़िगरेशन जोड़ता है।"
type: docs
weight: 300
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addfilter/
---
## AddFilter<TBuilder>(*this TBuilder, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter}

बिल्डर में एक 'filter' तत्व कॉन्फ़िगरेशन जोड़ता है।

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    Action<SVGFilterElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'filter' एलिमेंट के लिए कॉन्फ़िगरेशन एक्शन। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFilter<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter_1}

SVG बिल्डर में एक 'filter' तत्व जोड़ता है, जो SVG तत्वों पर लागू किया जा सकने वाला फ़िल्टर प्रभाव परिभाषित करता है।

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    CoordinateUnits? filterUnits = default, CoordinateUnits? primitiveUnits = default, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFilterElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | 'filter' एलिमेंट को जोड़े जाने वाला SVG बिल्डर इंस्टेंस। |
| filterUnits | फ़िल्टर के x, y, width, और height एट्रिब्यूट्स के लिए कोऑर्डिनेट सिस्टम निर्दिष्ट करता है। वैकल्पिक पैरामीटर। |
| primitiveUnits | फ़िल्टर के चाइल्ड एलिमेंट्स के एट्रिब्यूट्स के लिए कोऑर्डिनेट सिस्टम निर्दिष्ट करता है। वैकल्पिक पैरामीटर। |
| x | फ़िल्टर रीजन का x-कोऑर्डिनेट। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| y | फ़िल्टर रीजन का y-कोऑर्डिनेट। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| width | फ़िल्टर रीजन की चौड़ाई। यह डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| ऊँचाई | फ़िल्टर क्षेत्र की ऊँचाई। यह एक डबल या LengthType के साथ ValueTuple हो सकता है। वैकल्पिक पैरामीटर। |
| भरण | फ़िल्टर तत्व के लिए भरने का रंग या पेंट। वैकल्पिक पैरामीटर। |
| स्ट्रोक | फ़िल्टर तत्व के लिए स्ट्रोक रंग या पेंट। वैकल्पिक पैरामीटर। |
| id | फ़िल्टर तत्व के लिए अद्वितीय पहचानकर्ता। वैकल्पिक पैरामीटर। |
| विस्तार | SVGFilterElementBuilder को आगे कॉन्फ़िगर करने के लिए एक वैकल्पिक क्रिया। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* enum [CoordinateUnits](../../coordinateunits/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
