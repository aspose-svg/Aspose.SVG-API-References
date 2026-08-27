---
title: "SVGBuilderExtensions.TextLength"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions TextLength मेथड। टेक्स्ट सामग्री की सटीक लंबाई सेट करता है।"
type: docs
weight: 2220
url: /hi/net/aspose.svg.builder/svgbuilderextensions/textlength/
---
## SVGBuilderExtensions.TextLength<TBuilder> method

पाठ सामग्री की सटीक लंबाई सेट करता है।

```csharp
public static TBuilder TextLength<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| value | पाठ की लंबाई। |
| प्रकार | मान के लिए लंबाई इकाई का प्रकार। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

## टिप्पणियाँ

यह मेथड 'textLength' एट्रिब्यूट सेट करता है, जो टेक्स्ट सामग्री की इच्छित लंबाई निर्दिष्ट करता है, और संभवतः प्राकृतिक टेक्स्ट लंबाई को ओवरराइड कर सकता है।

### संबंधित देखें

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
