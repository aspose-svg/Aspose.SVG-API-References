---
title: "IDrawingFactory इंटरफ़ेस"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Drawing.IDrawingFactory इंटरफ़ेस। ड्राइंग-संबंधित ऑब्जेक्ट्स बनाने के लिए एक फ़ैक्टरी का प्रतिनिधित्व करता है"
type: docs
weight: 3460
url: /hi/net/aspose.svg.drawing/idrawingfactory/
---
## IDrawingFactory interface

ड्राइंग-संबंधित ऑब्जेक्ट्स बनाने के लिए एक फ़ैक्टरी का प्रतिनिधित्व करता है।

```csharp
public interface IDrawingFactory : IDisposable
```

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [CreateInterpolationColor](../../aspose.svg.drawing/idrawingfactory/createinterpolationcolor/)(*Color, float*) | निर्दिष्ट रंग और स्थिति के साथ एक इंटरपोलेशन रंग बनाता है। |
| [CreateLinearGradientBrush](../../aspose.svg.drawing/idrawingfactory/createlineargradientbrush/)(*RectangleF, IInterpolationColor[]*) | निर्दिष्ट पैरामीटरों के साथ एक लीनियर ग्रेडिएंट ब्रश बनाता है। |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix)() | एक नया आइडेंटिटी मैट्रिक्स बनाता है। |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_1)(*[IMatrix](../imatrix/)*) | निर्दिष्ट मैट्रिक्स के समान सामग्री के साथ एक नया मैट्रिक्स बनाता है। |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_2)(*float, float, float, float, float, float*) | निर्दिष्ट तत्वों के साथ एक नया मैट्रिक्स बनाता है। |
| [CreateSolidBrush](../../aspose.svg.drawing/idrawingfactory/createsolidbrush/)(*Color*) | निर्दिष्ट रंग के साथ एक ठोस ब्रश बनाता है। |
| [CreateTextureBrush](../../aspose.svg.drawing/idrawingfactory/createtexturebrush/)(*byte[]*) | निर्दिष्ट पैरामीटरों के साथ एक टेक्सचर ब्रश बनाता है। |

### संबंधित देखें

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
