---
title: "ComponentTransferType एनम"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Builder.ComponentTransferType एनम। SVG के FeComponentTransfer फ़िल्टर प्रिमिटिव में लागू किए जाने वाले कंपोनेंट ट्रांसफ़र फ़ंक्शन के प्रकार को निर्दिष्ट करता है।"
type: docs
weight: 170
url: /hi/net/aspose.svg.builder/componenttransfertype/
---
## ComponentTransferType enumeration

SVG के FeComponentTransfer फ़िल्टर प्रिमिटिव में लागू होने वाले कंपोनेंट ट्रांसफ़र फ़ंक्शन के प्रकार को निर्दिष्ट करता है।

```csharp
public enum ComponentTransferType
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Identity | `0` | इनपुट ग्राफ़िक में कोई परिवर्तन नहीं दर्शाता है। यह डिफ़ॉल्ट प्रकार है। |
| Table | `1` | फ़िल्टर के भीतर फ़ंक्शन को परिभाषित करने के लिए लुकअप टेबल का उपयोग करता है। |
| Discrete | `2` | फ़िल्टर में फ़ंक्शन को परिभाषित करने के लिए अलग-अलग मानों का सेट उपयोग करता है। |
| Linear | `3` | फ़िल्टर के भीतर कंपोनेंट का रैखिक रूपांतरण परिभाषित करता है। |
| Gamma | `4` | फ़िल्टर में गामा सुधार रूपांतरण को परिभाषित करता है। |

## टिप्पणियाँ

FeComponentTransfer फ़िल्टर प्रिमिटिव विभिन्न प्रकार के ट्रांसफ़र फ़ंक्शनों का उपयोग करके ग्राफ़िक्स तत्वों के रंग घटकों (RGB और अल्फा) की व्यक्तिगत हेरफेर की अनुमति देता है। प्रत्येक प्रकार फ़िल्टर के भीतर रंग घटक रूपांतरण के लिए एक विशिष्ट गणना विधि को परिभाषित करता है।

### संबंधित देखें

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
