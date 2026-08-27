---
title: "IMatrix Interface"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Drawing.IMatrix interface. रूपांतरणों के लिए उपयोग किए जाने वाले मैट्रिक्स को दर्शाता है"
type: docs
weight: 3500
url: /hi/net/aspose.svg.drawing/imatrix/
---
## IMatrix interface

रूपांतरणों के लिए उपयोग किए जाने वाले मैट्रिक्स को दर्शाता है।

```csharp
public interface IMatrix
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [IsIdentity](../../aspose.svg.drawing/imatrix/isidentity/) { get; } | यह प्राप्त करता है कि यह मैट्रिक्स पहचान मैट्रिक्स है या नहीं, यह दर्शाने वाला मान। |
| [IsInvertible](../../aspose.svg.drawing/imatrix/isinvertible/) { get; } | यह प्राप्त करता है कि यह मैट्रिक्स उलटा किया जा सकता है या नहीं, यह दर्शाने वाला मान। |
| [M11](../../aspose.svg.drawing/imatrix/m11/) { get; set; } | मैट्रिक्स की पहली पंक्ति और पहले कॉलम में मान को प्राप्त करता है या सेट करता है। |
| [M12](../../aspose.svg.drawing/imatrix/m12/) { get; set; } | मैट्रिक्स की पहली पंक्ति और दूसरे कॉलम में मान को प्राप्त करता है या सेट करता है। |
| [M21](../../aspose.svg.drawing/imatrix/m21/) { get; set; } | मैट्रिक्स की दूसरी पंक्ति और पहले कॉलम में मान प्राप्त करता है या सेट करता है। |
| [M22](../../aspose.svg.drawing/imatrix/m22/) { get; set; } | मैट्रिक्स की दूसरी पंक्ति और दूसरे कॉलम में मान प्राप्त करता है या सेट करता है। |
| [M31](../../aspose.svg.drawing/imatrix/m31/) { get; set; } | मैट्रिक्स की तीसरी पंक्ति और पहले कॉलम में मान प्राप्त करता है या सेट करता है। |
| [M32](../../aspose.svg.drawing/imatrix/m32/) { get; set; } | मैट्रिक्स की तीसरी पंक्ति और दूसरे कॉलम में मान प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Clone](../../aspose.svg.drawing/imatrix/clone/)() | इस मैट्रिक्स की एक कॉपी बनाता है। |
| [GetElements](../../aspose.svg.drawing/imatrix/getelements/)() | मैट्रिक्स के तत्वों को एक एरे के रूप में प्राप्त करता है। |
| [Invert](../../aspose.svg.drawing/imatrix/invert/)() | इस मैट्रिक्स को उलटता है। |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply)(*IMatrix*) | इस मैट्रिक्स को किसी अन्य मैट्रिक्स से गुणा करता है। |
| [Multiply](../../aspose.svg.drawing/imatrix/multiply/#multiply_1)(*IMatrix, [WebMatrixOrder](../webmatrixorder/)*) | निर्दिष्ट क्रम में इस मैट्रिक्स को किसी अन्य मैट्रिक्स से गुणा करता है। |
| [Reset](../../aspose.svg.drawing/imatrix/reset/)() | मैट्रिक्स को पहचान मैट्रिक्स में रीसेट करता है। |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate)(*float*) | मैट्रिक्स को निर्दिष्ट कोण से घुमाता है। |
| [Rotate](../../aspose.svg.drawing/imatrix/rotate/#rotate_1)(*float, [WebMatrixOrder](../webmatrixorder/)*) | निर्दिष्ट क्रम में मैट्रिक्स को निर्दिष्ट कोण से घुमाता है। |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat)(*float, PointF*) | मैट्रिक्स को निर्दिष्ट बिंदु के चारों ओर निर्दिष्ट कोण से घुमाता है। |
| [RotateAt](../../aspose.svg.drawing/imatrix/rotateat/#rotateat_1)(*float, PointF, [WebMatrixOrder](../webmatrixorder/)*) | निर्दिष्ट क्रम में मैट्रिक्स को निर्दिष्ट बिंदु के चारों ओर निर्दिष्ट कोण से घुमाता है। |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale)(*float, float*) | मैट्रिक्स को निर्दिष्ट स्केल फ़ैक्टरों से समान रूप से स्केल करता है। |
| [Scale](../../aspose.svg.drawing/imatrix/scale/#scale_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | निर्दिष्ट क्रम में मैट्रिक्स को निर्दिष्ट स्केल फ़ैक्टरों से स्केल करता है। |
| [Skew](../../aspose.svg.drawing/imatrix/skew/)(*float, float*) | मैट्रिक्स पर एक स्क्यू ट्रांसफ़ॉर्मेशन लागू करता है। |
| [TransformPoint](../../aspose.svg.drawing/imatrix/transformpoint/)(*PointF*) | इस मैट्रिक्स का उपयोग करके निर्दिष्ट बिंदु को ट्रांसफ़ॉर्म करता है। |
| [TransformPoints](../../aspose.svg.drawing/imatrix/transformpoints/)(*PointF[]*) | इस मैट्रिक्स का उपयोग करके बिंदुओं की एक एरे को ट्रांसफ़ॉर्म करता है। |
| [TransformRectangle](../../aspose.svg.drawing/imatrix/transformrectangle/)(*RectangleF*) | इस मैट्रिक्स का उपयोग करके निर्दिष्ट आयत को ट्रांसफ़ॉर्म करता है। |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate)(*float, float*) | मैट्रिक्स को निर्दिष्ट ऑफ़सेट मानों से ट्रांसलेट करता है। |
| [Translate](../../aspose.svg.drawing/imatrix/translate/#translate_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | निर्दिष्ट क्रम में मैट्रिक्स को निर्दिष्ट ऑफ़सेट मानों से ट्रांसलेट करता है। |

### संबंधित देखें

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
