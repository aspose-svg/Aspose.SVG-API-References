---
title: "SVGBuilderExtensions.OnAbort"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions OnAbort मेथड। onabort इवेंट एट्रिब्यूट सेट करता है जो SVG दस्तावेज़ के लोडिंग के रद्द होने पर चलने वाले स्क्रिप्ट को परिभाषित करता है।"
type: docs
weight: 1190
url: /hi/net/aspose.svg.builder/svgbuilderextensions/onabort/
---
## SVGBuilderExtensions.OnAbort<TBuilder> method

जब SVG दस्तावेज़ का लोडिंग रद्द हो जाता है, तब चलने वाले स्क्रिप्ट को परिभाषित करते हुए 'onabort' इवेंट विशेषता सेट करता है।

```csharp
public static TBuilder OnAbort<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentEventAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| value | दस्तावेज़ लोडिंग के रद्द होने पर चलाने के लिए जावास्क्रिप्ट फ़ंक्शन या स्क्रिप्ट। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

### संबंधित देखें

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentEventAttributeSetter](../../idocumenteventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
