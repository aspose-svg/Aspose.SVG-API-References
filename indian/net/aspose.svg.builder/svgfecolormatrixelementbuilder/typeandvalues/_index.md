---
title: "SVGFEColorMatrixElementBuilder.TypeAndValues"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGFEColorMatrixElementBuilder TypeAndValues मेथड। feColorMatrix तत्व के type और values गुणों को सेट करता है जो रंग मैट्रिक्स ऑपरेशन और उसके पैरामीटर को निर्दिष्ट करता है।"
type: docs
weight: 30
url: /hi/net/aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/
---
## SVGFEColorMatrixElementBuilder.TypeAndValues method

feColorMatrix एलिमेंट के 'type' और 'values' एट्रिब्यूट सेट करता है, जो कलर मैट्रिक्स ऑपरेशन और उसके पैरामीटर निर्दिष्ट करता है।

```csharp
public SVGFEColorMatrixElementBuilder TypeAndValues(ColorMatrixOperation type, 
    params double[] values)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| प्रकार | ColorMatrixOperation | ColorMatrixOperation एनीम मान जो रंग मैट्रिक्स ऑपरेशन के प्रकार को दर्शाता है। |
| values | Double[] | रंग मैट्रिक्स ऑपरेशन के पैरामीटर। |

### रिटर्न वैल्यू

वर्तमान बिल्डर इंस्टेंस।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | जब प्रदान किए गए मान निर्दिष्ट प्रकार की आवश्यकताओं से मेल नहीं खाते तो थ्रो किया जाता है। |
| NotSupportedException | जब असमर्थित मैट्रिक्स ऑपरेशन प्रकार प्रदान किया जाता है तो थ्रो किया जाता है। |

### संबंधित देखें

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [SVGFEColorMatrixElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
