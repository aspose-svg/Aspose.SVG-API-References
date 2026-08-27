---
title: "SVGBuilderExtensions.AddPolygon"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddPolygon मेथड। बिल्डर में एक पॉलीगॉन एलिमेंट कॉन्फ़िगरेशन जोड़ता है।"
type: docs
weight: 420
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addpolygon/
---
## AddPolygon<TBuilder>(*this TBuilder, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon_1}

बिल्डर में 'polygon' तत्व कॉन्फ़िगरेशन जोड़ता है।

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, 
    Action<SVGPolygonElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'polygon' एलिमेंट के लिए कॉन्फ़िगरेशन एक्शन। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolygon<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon}

SVG बिल्डर में 'polygon' तत्व जोड़ता है, जिसमें इसके शीर्ष बिंदु और शैलियों को निर्दिष्ट किया जाता है।

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolygonElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | 'polygon' एलिमेंट को जोड़े जाने वाला SVG बिल्डर इंस्टेंस। |
| points | डबल्स की एक एरे जो पॉलीगॉन के पॉइंट्स को दर्शाती है (वैकल्पिक x और y निर्देशांक)। |
| भरण | बहुभुज के लिए भरने का रंग या पेंट शैली। यह Color या Paint enum मान या पेंट सर्वर ID हो सकता है। वैकल्पिक पैरामीटर। |
| स्ट्रोक | बहुभुज के लिए स्ट्रोक रंग या पेंट शैली। यह Color या Paint enum मान या पेंट सर्वर ID हो सकता है। वैकल्पिक पैरामीटर। |
| id | बहुभुज तत्व के लिए अद्वितीय पहचानकर्ता। वैकल्पिक पैरामीटर। |
| विस्तार | बहुभुज तत्व बिल्डर को आगे कॉन्फ़िगर करने के लिए एक वैकल्पिक क्रिया। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
