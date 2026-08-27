---
title: "SVGBuilderExtensions.AddPattern"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions AddPattern मेथड। बिल्डर में एक पैटर्न एलिमेंट कॉन्फ़िगरेशन जोड़ता है।"
type: docs
weight: 410
url: /hi/net/aspose.svg.builder/svgbuilderextensions/addpattern/
---
## AddPattern<TBuilder>(*this TBuilder, Action&lt;SVGPatternElementBuilder&gt;*) {#addpattern}

बिल्डर में 'pattern' तत्व कॉन्फ़िगरेशन जोड़ता है।

```csharp
public static TBuilder AddPattern<TBuilder>(this TBuilder builder, 
    Action<SVGPatternElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| कॉन्फ़िगर करें | 'pattern' एलिमेंट के लिए कॉन्फ़िगरेशन एक्शन। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [SVGPatternElementBuilder](../../svgpatternelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPattern<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, string, string, Action&lt;SVGPatternElementBuilder&gt;*) {#addpattern_1}

SVG बिल्डर में 'pattern' तत्व जोड़ता है, जिसमें पैटर्न की सामग्री के लिए समन्वय प्रणाली और इकाइयों को निर्दिष्ट किया जाता है।

```csharp
public static TBuilder AddPattern<TBuilder>(this TBuilder builder, CoordinateUnits? patternUnits, 
    CoordinateUnits? patternContentUnits, string href = null, string id = null, 
    Action<SVGPatternElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार, जो सहज API उपयोग को सुविधाजनक बनाता है। |
| बिल्डर | 'pattern' एलिमेंट को जोड़े जाने वाला SVG बिल्डर इंस्टेंस। |
| patternUnits | पैटर्न के लिए कोऑर्डिनेट सिस्टम निर्दिष्ट करता है। वैकल्पिक पैरामीटर। |
| patternContentUnits | पैटर्न के भीतर कंटेंट के लिए कोऑर्डिनेट सिस्टम निर्दिष्ट करता है। वैकल्पिक पैरामीटर। |
| href | यदि लागू हो, तो दूसरे पैटर्न का रेफ़रेंस। वैकल्पिक पैरामीटर। |
| id | पैटर्न एलिमेंट के लिए अद्वितीय पहचानकर्ता। वैकल्पिक पैरामीटर। |
| विस्तार | पैटर्न एलिमेंट बिल्डर को आगे कॉन्फ़िगर करने के लिए वैकल्पिक एक्शन। |

### रिटर्न वैल्यू

बिल्डर इंस्टेंस, जो मेथड चेनिंग की अनुमति देता है।

### संबंधित देखें

* enum [CoordinateUnits](../../coordinateunits/)
* class [SVGPatternElementBuilder](../../svgpatternelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
