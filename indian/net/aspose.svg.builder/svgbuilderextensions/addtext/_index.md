---
title: "SVGBuilderExtensions.AddText"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddText मेथड। बिल्डर में एक टेक्स्ट एलिमेंट कॉन्फ़िगरेशन जोड़ता है"
type: docs
weight: 530
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addtext/
---
## AddText<TBuilder>(*this TBuilder, Action&lt;SVGTextElementBuilder&gt;*) {#addtext}

बिल्डर में 'text' तत्व कॉन्फ़िगरेशन जोड़ता है।

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, 
    Action<SVGTextElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'text' एलिमेंट के लिए कॉन्फ़िगरेशन एक्शन। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddText<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, FontStyle?, string, FontWeight?, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGTextElementBuilder&gt;*) {#addtext_1}

SVG बिल्डर में निर्दिष्ट सामग्री और गुणों के साथ 'text' तत्व जोड़ता है।

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, string content, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> fontSize = null, FontStyle? fontStyle = default, 
    string fontFamily = null, FontWeight? fontWeight = default, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGTextElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG एलिमेंट बिल्डर का टाइप, जो चेनिंग की अनुमति देता है। |
| बिल्डर | 'text' एलिमेंट को जोड़ने के लिए बिल्डर इंस्टेंस। |
| content | 'text' एलिमेंट के भीतर प्रदर्शित होने वाला टेक्स्ट कंटेंट। |
| x | टेक्स्ट एलिमेंट के लिए x-कोऑर्डिनेट। यह डबल वैल्यू या डबल और LengthType के ट्यूपल हो सकता है। |
| y | टेक्स्ट एलिमेंट के लिए y-कोऑर्डिनेट। यह डबल वैल्यू या डबल और LengthType के ट्यूपल हो सकता है। |
| fontSize | टेक्स्ट के लिए फ़ॉन्ट साइज। यह डबल वैल्यू या डबल और LengthType के ट्यूपल हो सकता है। |
| fontStyle | टेक्स्ट के लिए फ़ॉन्ट स्टाइल (जैसे, normal, italic, oblique)। |
| fontFamily | टेक्स्ट के लिए फ़ॉन्ट फ़ैमिली (जैसे, Arial, Verdana)। |
| fontWeight | फ़ॉन्ट का वेट (थिकनेस) (जैसे, normal, bold)। |
| भरण | टेक्स्ट के लिए फ़िल कलर या पेंट स्टाइल। यह Color या Paint एन्‍युम वैल्यू या पेंट सर्वर ID हो सकता है। |
| स्ट्रोक | टेक्स्ट के लिए स्ट्रोक कलर या पेंट स्टाइल। यह Color या Paint एन्‍युम वैल्यू या पेंट सर्वर ID हो सकता है। |
| id | पाठ तत्व के लिए अद्वितीय पहचानकर्ता। |
| विस्तार | पाठ तत्व बिल्डर को आगे कॉन्फ़िगर करने के लिए एक वैकल्पिक कार्रवाई। |

### रिटर्न वैल्यू

आगे के जोड़ या कॉन्फ़िगरेशन को श्रृंखलाबद्ध करने के लिए बिल्डर इंस्टेंस।

### संबंधित देखें

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [FontStyle](../../fontstyle/)
* enum [FontWeight](../../fontweight/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
