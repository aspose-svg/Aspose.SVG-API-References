---
title: "SVGBuilderExtensions.FontKerning"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions FontKerning मेथड। संख्यात्मक मान और विशिष्ट लंबाई प्रकार का उपयोग करके SVG तत्व के लिए font-kerning एट्रिब्यूट सेट करता है।"
type: docs
weight: 880
url: /hi/net/aspose.svg.builder/svgbuilderextensions/fontkerning/
---
## FontKerning<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#fontkerning_1}

संख्यात्मक मान और विशिष्ट लंबाई प्रकार का उपयोग करके SVG तत्व के लिए 'font-kerning' विशेषता सेट करता है।

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| value | सेट करने के लिए फ़ॉन्ट कर्निंग मान। |
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

## FontKerning<TBuilder>(*this TBuilder, [Kerning](../../kerning/)*) {#fontkerning}

पूर्वनिर्धारित kerning मान का उपयोग करके SVG तत्व के लिए 'font-kerning' विशेषता सेट करता है।

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, Kerning value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| value | सेट करने के लिए पूर्वनिर्धारित कर्निंग मान। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* enum [Kerning](../../kerning/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
