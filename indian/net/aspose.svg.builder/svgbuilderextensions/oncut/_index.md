---
title: "SVGBuilderExtensions.OnCut"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions OnCut मेथड। SVG एलिमेंट से कंटेंट कट होने पर चलने वाली स्क्रिप्ट को परिभाषित करने वाला oncut इवेंट एट्रिब्यूट सेट करता है"
type: docs
weight: 1290
url: /hi/net/aspose.svg.builder/svgbuilderextensions/oncut/
---
## SVGBuilderExtensions.OnCut<TBuilder> method

जब SVG तत्व से सामग्री कट की जाती है, तब चलने वाले स्क्रिप्ट को परिभाषित करते हुए 'oncut' इवेंट विशेषता सेट करता है।

```csharp
public static TBuilder OnCut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| value | कट इवेंट पर चलाने के लिए JavaScript फ़ंक्शन या स्क्रिप्ट। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
