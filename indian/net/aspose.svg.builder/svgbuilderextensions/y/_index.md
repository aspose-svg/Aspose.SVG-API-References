---
title: "SVGBuilderExtensions.Y"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions Y मेथड। एक SVG तत्व के लिए y एट्रिब्यूट सेट करता है।"
type: docs
weight: 2400
url: /hi/net/aspose.svg.builder/svgbuilderextensions/y/
---
## Y<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#y_1}

SVG तत्व के लिए 'y' विशेषता सेट करता है।

```csharp
public static TBuilder Y<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IYAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| value | 'y' एट्रिब्यूट का मान। |
| प्रकार | लंबाई माप का प्रकार (डिफ़ॉल्ट पिक्सेल है)। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IYAttributeSetter](../../iyattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Y<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#y}

पाठ सामग्री को y-अक्ष के साथ स्थित करने के लिए 'y' विशेषता सेट करता है।

```csharp
public static TBuilder Y<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| प्रकार | मानों के लिए लंबाई इकाई का प्रकार। |
| values | y-अक्ष स्थितियों के मान। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

## टिप्पणियाँ

यह मेथड 'y' एट्रिब्यूट सेट करता है, जो टेक्स्ट तत्व की ऊर्ध्वाधर स्थिति निर्धारित करता है।

### संबंधित देखें

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
