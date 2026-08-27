---
title: "SVGBuilderExtensions.OnFocusIn"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGBuilderExtensions OnFocusIn मेथड। तत्व पर फोकस-इन इवेंट को संभालने के लिए onfocusin इवेंट एट्रिब्यूट सेट करता है।"
type: docs
weight: 1450
url: /hi/net/aspose.svg.builder/svgbuilderextensions/onfocusin/
---
## SVGBuilderExtensions.OnFocusIn<TBuilder> method

तत्व पर फोकस-इन इवेंट को संभालने के लिए 'onfocusin' इवेंट एट्रिब्यूट सेट करता है।

```csharp
public static TBuilder OnFocusIn<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| पैरामीटर | विवरण |
| --- | --- |
| TBuilder | SVG तत्व बिल्डर का प्रकार। |
| बिल्डर | SVG तत्व बिल्डर। |
| value | जब तत्व फोकस प्राप्त करता है, तब चलाने के लिए जावास्क्रिप्ट फ़ंक्शन या स्क्रिप्ट, आमतौर पर 'onfocus' इवेंट से पहले। |

### रिटर्न वैल्यू

चेनिंग के लिए बिल्डर का उदाहरण।

## टिप्पणियाँ

जब कोई तत्व फोकस प्राप्त करने वाला होता है, तब 'onfocusin' इवेंट ट्रिगर होता है। यह इवेंट 'onfocus' से अलग है क्योंकि यह बबलिंग को सपोर्ट करता है और इसका उपयोग चाइल्ड तत्वों में फोकस परिवर्तन का पता लगाने के लिए भी किया जा सकता है।

### संबंधित देखें

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
