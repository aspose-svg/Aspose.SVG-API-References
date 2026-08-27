---
title: "SVGBuilderExtensions.RefX"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions RefX मेथड। SVG तत्व के लिए refX एट्रिब्यूट सेट करता है।"
type: docs
weight: 1930
url: /hi/net/aspose.svg.builder/svgbuilderextensions/refx/
---
## RefX<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#refx_1}

एक SVG तत्व के लिए 'refX' एट्रिब्यूट सेट करता है।

```csharp
public static TBuilder RefX<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IRefCoordinatesAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| value | संदर्भ X निर्देशांक। |
| प्रकार | लंबाई इकाई का प्रकार (डिफ़ॉल्ट पिक्सेल है)। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRefCoordinatesAttributeSetter](../../irefcoordinatesattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RefX<TBuilder>(*this TBuilder, [HorizontalPosition](../../horizontalposition/)*) {#refx}

पूर्वनिर्धारित क्षैतिज स्थिति का उपयोग करके एक SVG तत्व के लिए 'refX' एट्रिब्यूट सेट करता है।

```csharp
public static TBuilder RefX<TBuilder>(this TBuilder builder, HorizontalPosition value)
    where TBuilder : ISVGElementBuilder, IRefCoordinatesAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | बिल्डर का उदाहरण। |
| value | पूर्वनिर्धारित क्षैतिज स्थिति। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* enum [HorizontalPosition](../../horizontalposition/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IRefCoordinatesAttributeSetter](../../irefcoordinatesattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
