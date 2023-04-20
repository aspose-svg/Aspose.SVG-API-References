---
title: Class ImageDevice
second_title: .NET API संदर्भ के लिए Aspose.SVG
description: Aspose.Svg.Rendering.Image.ImageDevice कक्ष. रेखपुंज स्वरूपं में रेंडरंग क प्रतनधत्व करत है jpeg png bmp gif tiff.
type: docs
weight: 2830
url: /hi/net/aspose.svg.rendering.image/imagedevice/
---
## ImageDevice class

रेखापुंज स्वरूपों में रेंडरिंग का प्रतिनिधित्व करता है: jpeg, png, bmp, gif, tiff.

```csharp
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | का एक नया उदाहरण प्रारंभ करता है`ImageDevice` वर्ग. |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | का एक नया उदाहरण प्रारंभ करता है`ImageDevice` वर्ग. |
| [ImageDevice](imagedevice/#constructor_5)(string) | का एक नया उदाहरण प्रारंभ करता है`ImageDevice` वर्ग. |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | का एक नया उदाहरण प्रारंभ करता है`ImageDevice` रेंडरिंग विकल्प और स्ट्रीम प्रदाता द्वारा वर्ग। |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | का एक नया उदाहरण प्रारंभ करता है`ImageDevice` विकल्प और आउटपुट स्ट्रीम प्रदान करके वर्ग। |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, string) | का एक नया उदाहरण प्रारंभ करता है`ImageDevice` विकल्प और आउटपुट फ़ाइल नाम प्रदान करके वर्ग। |

## गुण

| नाम | विवरण |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } |  |
| virtual [Graphics](../../aspose.svg.rendering.image/imagedevice/graphics/) { get; } | ग्राफिक्स का उदाहरण प्राप्त करता है। |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } |  |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [AddRect](../../aspose.svg.rendering.image/imagedevice/addrect/)(RectangleF) | एक पूर्ण उपपथ के रूप में वर्तमान पथ में एक आयत जोड़ता है। |
| override [BeginDocument](../../aspose.svg.rendering.image/imagedevice/begindocument/)(Document) | दस्तावेज़ का प्रतिपादन शुरू करता है। |
| override [BeginElement](../../aspose.svg.rendering.image/imagedevice/beginelement/)(Element, RectangleF) | तत्व का प्रतिपादन शुरू करता है। |
| override [BeginPage](../../aspose.svg.rendering.image/imagedevice/beginpage/)(SizeF) | नए पेज की रेंडरिंग शुरू करता है। |
| override [Clip](../../aspose.svg.rendering.image/imagedevice/clip/)(FillMode) | भरने के क्षेत्र को निर्धारित करने के लिए फिलमोड नियम का उपयोग करके वर्तमान क्लिपिंग पथ को वर्तमान पथ से काटकर संशोधित करता है। यह विधि वर्तमान पथ को समाप्त करती है। |
| override [ClosePath](../../aspose.svg.rendering.image/imagedevice/closepath/)() | वर्तमान बिंदु से उपपथ के प्रारंभिक बिंदु तक एक सीधी रेखा खंड जोड़कर वर्तमान उपपथ को बंद करता है। यदि वर्तमान उपपथ पहले से ही बंद है, तो "ClosePath" कुछ नहीं करता है। यह ऑपरेटर वर्तमान उपपथ को समाप्त कर देता है। वर्तमान पथ में एक और खंड जोड़ने से एक नया उपपथ शुरू होता है, भले ही नया खंड "क्लोजपाथ" विधि द्वारा पहुंचे समापन बिंदु पर शुरू होता है। |
| override [CubicBezierTo](../../aspose.svg.rendering.image/imagedevice/cubicbezierto/)(PointF, PointF, PointF) | एक घन बेज़ियर वक्र को वर्तमान पथ में जोड़ता है। वक्र वर्तमान बिंदु से बिंदु pt2, तक pt1 और pt2 को बेज़ियर नियंत्रण बिंदुओं के रूप में उपयोग करता है। नया वर्तमान बिंदु pt3. है |
| [Dispose](../../aspose.svg.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.svg.rendering.image/imagedevice/drawimage/)(byte[], ImageType, RectangleF) | निर्दिष्ट छवि बनाता है। |
| override [EndDocument](../../aspose.svg.rendering.image/imagedevice/enddocument/)() | दस्तावेज़ का प्रतिपादन समाप्त करता है। |
| override [EndElement](../../aspose.svg.rendering.image/imagedevice/endelement/)(Element) | तत्व का प्रतिपादन समाप्त करता है। |
| override [EndPage](../../aspose.svg.rendering.image/imagedevice/endpage/)() | वर्तमान पृष्ठ का प्रतिपादन समाप्त करता है। |
| override [Fill](../../aspose.svg.rendering.image/imagedevice/fill/)(FillMode) | वर्तमान पथ से घिरे पूरे क्षेत्र को भरता है। यदि पथ में कई डिस्कनेक्ट किए गए उपपथ होते हैं, तो यह सभी उपपथों के अंदर भरता है, को एक साथ माना जाता है। यह विधि वर्तमान पथ को समाप्त करती है। |
| override [FillText](../../aspose.svg.rendering.image/imagedevice/filltext/)(string, PointF) | निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट स्थान पर भरता है। |
| override [Flush](../../aspose.svg.rendering.image/imagedevice/flush/)() | सभी डेटा को आउटपुट स्ट्रीम में फ़्लश करता है. |
| override [LineTo](../../aspose.svg.rendering.image/imagedevice/lineto/)(PointF) | वर्तमान बिंदु से बिंदु (पीटी) तक एक सीधी रेखा खंड जोड़ता है। नया वर्तमान बिंदु pt. है |
| override [MoveTo](../../aspose.svg.rendering.image/imagedevice/moveto/)(PointF) | किसी भी कनेक्टिंग लाइन सेगमेंट को छोड़ते हुए, वर्तमान बिंदु को पैरामीटर pt के निर्देशांक में ले जाकर एक नया उपपथ शुरू करता है। यदि वर्तमान पथ में पिछली पथ निर्माण विधि भी "MoveTo" थी, तो नई "MoveTo" इसे ओवरराइड कर देती है; पिछले "मूव टू" ऑपरेशन का कोई अवशेष पथ में नहीं रहता है। |
| override [RestoreGraphicContext](../../aspose.svg.rendering.image/imagedevice/restoregraphiccontext/)() | पूरे ग्राफिक्स संदर्भ को स्टैक से पॉप करके उसके पूर्व मान पर पुनर्स्थापित करता है। |
| override [SaveGraphicContext](../../aspose.svg.rendering.image/imagedevice/savegraphiccontext/)() | स्टैक पर संपूर्ण ग्राफ़िक्स संदर्भ की एक प्रति पुश करता है. |
| override [Stroke](../../aspose.svg.rendering.image/imagedevice/stroke/)() | वर्तमान पथ के साथ एक रेखा को स्ट्रोक करता है। स्ट्रोक की गई रेखा पथ में प्रत्येक सीधे या घुमावदार खंड का अनुसरण करती है, इसके समानांतर भुजाओं वाले खंड पर केंद्रित होती है। पथ के प्रत्येक उपपथ को अलग से व्यवहार किया जाता है। यह विधि वर्तमान पथ को समाप्त करती है। |
| override [StrokeAndFill](../../aspose.svg.rendering.image/imagedevice/strokeandfill/)(FillMode) | स्ट्रोक और वर्तमान पथ भरें। यह विधि वर्तमान पथ को समाप्त करती है। |
| override [StrokeText](../../aspose.svg.rendering.image/imagedevice/stroketext/)(string, PointF) | निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट स्थान पर स्ट्रोक करता है। |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| class [ImageGraphicContext](imagedevice.imagegraphiccontext/) | के लिए वर्तमान ग्राफिक्स नियंत्रण पैरामीटर रखता है`ImageDevice`. ये पैरामीटर वैश्विक ढांचे को परिभाषित करते हैं जिसके भीतर ग्राफिक्स ऑपरेटर निष्पादित करते हैं। |

### यह सभी देखें

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.svg.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* नाम स्थान [Aspose.Svg.Rendering.Image](../../aspose.svg.rendering.image/)
* सभा [Aspose.SVG](../../)


