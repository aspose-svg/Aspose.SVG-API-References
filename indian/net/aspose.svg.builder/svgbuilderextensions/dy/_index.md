---
title: "SVGBuilderExtensions.Dy"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions Dy मेथड। टेक्स्ट सामग्री के लिए कई ऊर्ध्वाधर समायोजन मान सेट करता है।"
type: docs
weight: 780
url: /hi/net/aspose.svg.builder/svgbuilderextensions/dy/
---
## Dy<TBuilder>(*this TBuilder, double[], [LengthType](../../lengthtype/)*) {#dy_1}

पाठ सामग्री के लिए कई लंबवत समायोजन मान सेट करता है।

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double[] values, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| values | ऊर्ध्वाधर समायोजन मानों की एरे। |
| प्रकार | मानों के लिए लंबाई इकाई का प्रकार। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

## टिप्पणियाँ

यह विधि 'dy' विशेषता को कई मानों के साथ सेट करती है, जिससे प्रत्येक अक्षर या पाठ खंड के लिए व्यक्तिगत ऊर्ध्वाधर समायोजन संभव होते हैं।

### संबंधित देखें

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dy<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dy}

पाठ सामग्री के लिए एकल लंबवत समायोजन मान सेट करता है।

```csharp
public static TBuilder Dy<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| value | ऊर्ध्वाधर समायोजन मान। |
| प्रकार | मान के लिए लंबाई इकाई का प्रकार। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

## टिप्पणियाँ

यह विधि 'dy' विशेषता को एकल मान के साथ सेट करती है, जिससे पाठ सामग्री की ऊर्ध्वाधर स्थिति समायोजित होती है।

### संबंधित देखें

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
