---
title: "SVGBuilderExtensions.OnFocusOut"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions OnFocusOut मेथड। एलिमेंट पर फोकस-आउट इवेंट को संभालने के लिए onfocusout इवेंट एट्रिब्यूट सेट करता है"
type: docs
weight: 1460
url: /hi/net/aspose.svg.builder/svgbuilderextensions/onfocusout/
---
## SVGBuilderExtensions.OnFocusOut<TBuilder> method

तत्व पर फोकस-आउट इवेंट को संभालने के लिए 'onfocusout' इवेंट एट्रिब्यूट सेट करता है।

```csharp
public static TBuilder OnFocusOut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| value | एलिमेंट के फोकस खोने पर चलाने के लिए जावास्क्रिप्ट फ़ंक्शन या स्क्रिप्ट, आमतौर पर 'onblur' इवेंट से पहले। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

## टिप्पणियाँ

'onfocusout' इवेंट तब ट्रिगर होता है जब कोई एलिमेंट फोकस खोने वाला होता है। 'onfocusin' के समान, यह इवेंट बबलिंग का समर्थन करता है और चाइल्ड एलिमेंट्स में फोकस परिवर्तन का पता लगाने के लिए भी उपयोग किया जा सकता है।

### संबंधित देखें

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
