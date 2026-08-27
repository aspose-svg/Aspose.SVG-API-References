---
title: "SVGBuilderExtensions.Rotate"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions Rotate method. टेक्स्ट सामग्री के व्यक्तिगत अक्षरों या खंडों के लिए घूर्णन कोण सेट करता है।"
type: docs
weight: 2000
url: /hi/net/aspose.svg.builder/svgbuilderextensions/rotate/
---
## Rotate<TBuilder>(*this TBuilder, params double[]*) {#rotate_1}

पाठ सामग्री के व्यक्तिगत अक्षरों या खंडों के लिए घूर्णन कोण निर्धारित करता है।

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| values | डिग्री में घूर्णन कोणों की एक सरणी। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

## टिप्पणियाँ

यह विधि कई मानों के साथ 'rotate' विशेषता सेट करती है, जिससे प्रत्येक अक्षर या टेक्स्ट खंड का व्यक्तिगत घूर्णन संभव होता है।

### संबंधित देखें

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Rotate<TBuilder>(*this TBuilder, double*) {#rotate}

पूरे टेक्स्ट कंटेंट के लिए एकल घूर्णन कोण सेट करता है।

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, double value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| value | डिग्री में घूर्णन कोण। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

## टिप्पणियाँ

यह विधि एकल मान के साथ 'rotate' विशेषता सेट करती है, जिससे सभी टेक्स्ट सामग्री पर समान घूर्णन कोण लागू होता है।

### संबंधित देखें

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
