---
title: "Resource क्लास"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Saving.Resource class. यह क्लास एक संसाधन का वर्णन करती है और उसे प्रोसेस करने के लिए मेथड्स प्रदान करती है"
type: docs
weight: 5710
url: /hi/net/aspose.svg.saving/resource/
---
## Resource class

यह क्लास एक संसाधन का वर्णन करती है और उसे प्रोसेस करने के लिए मेथड्स प्रदान करती है।

```csharp
public class Resource
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [MimeType](../../aspose.svg.saving/resource/mimetype/) { get; } | इस संसाधन का !:Html.MimeType लौटाता है। यदि संसाधन नहीं मिला तो यह `null` हो सकता है। |
| [OriginalReference](../../aspose.svg.saving/resource/originalreference/) { get; } | इस संसाधन के मूल संदर्भ को शामिल करने वाली स्ट्रिंग लौटाता है। |
| [OriginalUrl](../../aspose.svg.saving/resource/originalurl/) { get; } | एक URL लौटाता है जो दर्शाता है कि यह संसाधन कहाँ स्थित था। |
| [OutputUrl](../../aspose.svg.saving/resource/outputurl/) { get; set; } | प्रोसेसिंग के बाद संसाधन जहाँ स्थित होगा, उसे दर्शाने वाला URL प्राप्त करता है या सेट करता है। |
| [Status](../../aspose.svg.saving/resource/status/) { get; } | संसाधन की वर्तमान स्थिति लौटाता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Embed](../../aspose.svg.saving/resource/embed/)(*[ResourceHandlingContext](../resourcehandlingcontext/)*) | इस संसाधन को उसके पैरेंट में Base64 के रूप में एन्कोड करके एम्बेड करता है। एन्कोडिंग परिणाम [`OutputUrl`](./outputurl/) पर लिखा जाएगा। |
| [Save](../../aspose.svg.saving/resource/save/)(*Stream, [ResourceHandlingContext](../resourcehandlingcontext/)*) | प्रदान किए गए स्ट्रीम में संसाधन को सहेजता है। |
| [WithOutputUrl](../../aspose.svg.saving/resource/withoutputurl/)(*[Url](../../aspose.svg/url/)*) | प्रोसेसिंग के बाद संसाधन जहाँ स्थित होगा, उसे दर्शाने वाला नया URL निर्दिष्ट करता है। |

### संबंधित देखें

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
