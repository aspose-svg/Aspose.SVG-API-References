---
title: "SVGGeometryElement.Combine"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGGeometryElement Combine मेथड। यह जियोमेट्री को एक बूलियन ऑपरेशन का उपयोग करके दूसरी SVG जियोमेट्री के साथ मिलाता है और परिणाम को शामिल करने वाला नया पाथ एलिमेंट लौटाता है"
type: docs
weight: 20
url: /hi/net/aspose.svg/svggeometryelement/combine/
---
## SVGGeometryElement.Combine method

यह जियोमेट्री को एक बूलियन ऑपरेशन का उपयोग करके दूसरी SVG जियोमेट्री के साथ मिलाता है, और परिणाम को शामिल करने वाला नया `<path>` एलिमेंट लौटाता है।

```csharp
public SVGPathElement Combine(SVGGeometryElement geometryElement, BooleanPathOp op)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| geometryElement | SVGGeometryElement | जिस अन्य जियोमेट्री को मिलाना है। यह समान दस्तावेज़ में होना चाहिए। |
| op | BooleanPathOp | लागू करने के लिए बूलियन ऑपरेटर: यूनियन (A UNION B), डिफरेंस (A - B), इंटरसेक्शन (A INTERSECT B), या एक्सक्लूजन (XOR)। |

### रिटर्न वैल्यू

एक नया [`SVGPathElement`](../../svgpathelement/) जिसका `d` एट्रिब्यूट परिणाम को रूट `<svg>` यूज़र स्पेस (CSS px) में एन्कोड करता है। यह एलिमेंट DOM में जोड़ा नहीं गया है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | यदि *geometryElement* null है तो फेंका जाता है। |
| InvalidOperationException | यदि इस एलिमेंट का कोई ओनर डॉक्यूमेंट नहीं है तो फेंका जाता है। |
| NotSupportedException | जब बूलियन पाथ ऑपरेशन्स उपलब्ध नहीं होते हैं तो फेंका जाता है; इस फीचर को SkiaSharp बैकएंड की आवश्यकता होती है (Aspose.SVG.Drawing.SkiaSharp पैकेज इंस्टॉल करें)। |

### संबंधित देखें

* class [SVGPathElement](../../svgpathelement/)
* enum [BooleanPathOp](../../../aspose.svg.rendering/booleanpathop/)
* class [SVGGeometryElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
