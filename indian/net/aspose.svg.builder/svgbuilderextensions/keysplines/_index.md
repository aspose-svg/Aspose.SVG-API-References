---
title: "SVGBuilderExtensions.KeySplines"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions KeySplines विधि। keySplines विशेषता सेट करती है जो एनीमेशन की गति के लिए नियंत्रण बिंदुओं को निर्दिष्ट करती है।"
type: docs
weight: 1060
url: /hi/net/aspose.svg.builder/svgbuilderextensions/keysplines/
---
## SVGBuilderExtensions.KeySplines<TBuilder> method

'keySplines' एट्रिब्यूट सेट करता है, जो एनीमेशन की गति के नियंत्रण बिंदु निर्दिष्ट करता है।

```csharp
public static TBuilder KeySplines<TBuilder>(this TBuilder builder, 
    Action<AnimationSplineBuilder> buildSplines)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| buildSplines | स्प्लाइन कॉन्फ़िगरेशन बनाने की क्रिया। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* class [AnimationSplineBuilder](../../animationsplinebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
