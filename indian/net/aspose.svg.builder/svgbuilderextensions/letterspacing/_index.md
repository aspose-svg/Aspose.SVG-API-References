---
title: "SVGBuilderExtensions.LetterSpacing"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions LetterSpacing मेथड। संख्यात्मक मान और विशिष्ट लंबाई प्रकार का उपयोग करके SVG तत्व के लिए letter-spacing एट्रिब्यूट सेट करता है"
type: docs
weight: 1100
url: /hi/net/aspose.svg.builder/svgbuilderextensions/letterspacing/
---
## LetterSpacing<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#letterspacing_1}

SVG तत्व के लिए 'letter-spacing' एट्रिब्यूट को एक संख्यात्मक मान और एक विशिष्ट लंबाई प्रकार का उपयोग करके सेट करता है।

```csharp
public static TBuilder LetterSpacing<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| value | सेट करने के लिए अक्षर अंतर मान। |
| प्रकार | लंबाई प्रकार (जैसे, px, em)। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## LetterSpacing<TBuilder>(*this TBuilder, [Spacing](../../spacing/)*) {#letterspacing}

SVG तत्व के लिए 'letter-spacing' एट्रिब्यूट को एक पूर्वनिर्धारित स्पेसिंग मान का उपयोग करके सेट करता है।

```csharp
public static TBuilder LetterSpacing<TBuilder>(this TBuilder builder, Spacing value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| value | सेट करने के लिए पूर्वनिर्धारित अंतर मान। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* enum [Spacing](../../spacing/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
