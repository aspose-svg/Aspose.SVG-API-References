---
title: "SVGBuilderExtensions.Dx"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions Dx method. टेक्स्ट में प्रत्येक अक्षर की क्षैतिज स्थिति को समायोजित करने के लिए dx एट्रिब्यूट सेट करता है।"
type: docs
weight: 770
url: /hi/net/aspose.svg.builder/svgbuilderextensions/dx/
---
## Dx<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#dx}

'dx' विशेषता सेट करता है ताकि पाठ में प्रत्येक अक्षर की क्षैतिज स्थिति समायोजित की जा सके।

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| प्रकार | मानों के लिए लंबाई इकाई का प्रकार। |
| values | प्रत्येक अक्षर के लिए क्षैतिज समायोजन मान। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

## टिप्पणियाँ

यह मेथड टेक्स्ट में अक्षरों के क्षैतिज स्पेसिंग पर सूक्ष्म नियंत्रण प्रदान करता है।

### संबंधित देखें

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dx<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dx_1}

पाठ सामग्री के लिए एकल क्षैतिज समायोजन मान सेट करता है।

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| value | क्षैतिज समायोजन मान। |
| प्रकार | मान के लिए लंबाई इकाई का प्रकार। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

## टिप्पणियाँ

यह मेथड 'dx' एट्रिब्यूट को एकल मान के साथ सेट करता है, जिससे टेक्स्ट कंटेंट की क्षैतिज स्थिति समायोजित होती है।

### संबंधित देखें

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
