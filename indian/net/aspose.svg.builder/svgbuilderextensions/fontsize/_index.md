---
title: "SVGBuilderExtensions.FontSize"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions FontSize मेथड। संख्यात्मक मान और विशिष्ट लंबाई प्रकार का उपयोग करके SVG तत्व के लिए font-size एट्रिब्यूट सेट करता है।"
type: docs
weight: 890
url: /hi/net/aspose.svg.builder/svgbuilderextensions/fontsize/
---
## FontSize<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#fontsize_1}

SVG तत्व के लिए 'font-size' एट्रिब्यूट को एक संख्यात्मक मान और एक विशिष्ट लंबाई प्रकार का उपयोग करके सेट करता है।

```csharp
public static TBuilder FontSize<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| value | सेट करने के लिए फ़ॉन्ट आकार मान। |
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

## FontSize<TBuilder>(*this TBuilder, [FontSize](../../fontsize/)*) {#fontsize}

पूर्वनिर्धारित फ़ॉन्ट आकार मान का उपयोग करके SVG तत्व के लिए 'font-size' विशेषता सेट करता है।

```csharp
public static TBuilder FontSize<TBuilder>(this TBuilder builder, FontSize value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| value | सेट करने हेतु पूर्वनिर्धारित फ़ॉन्ट आकार मान। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* enum [FontSize](../../fontsize/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
