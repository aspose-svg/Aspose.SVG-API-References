---
title: "FileSystemResourceHandler क्लास"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Saving.ResourceHandlers.FileSystemResourceHandler क्लास। यह क्लास ResourceHandler क्लास का एक कार्यान्वयन है जो संसाधनों को स्थानीय फ़ाइल सिस्टम में सहेजने के लिए डिज़ाइन किया गया है"
type: docs
weight: 5720
url: /hi/net/aspose.svg.saving.resourcehandlers/filesystemresourcehandler/
---
## FileSystemResourceHandler class

यह क्लास [`ResourceHandler`](../resourcehandler/) क्लास का एक कार्यान्वयन है जो संसाधनों को स्थानीय फ़ाइल सिस्टम में सहेजने के लिए डिज़ाइन किया गया है।

```csharp
public class FileSystemResourceHandler : ResourceHandler
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor_1)(*string*) | `FileSystemResourceHandler` क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor)(*[Url](../../aspose.svg/url/)*) | `FileSystemResourceHandler` क्लास का एक नया इंस्टेंस प्रारंभ करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [HandleResource](../../aspose.svg.saving.resourcehandlers/filesystemresourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | यह विधि संसाधन को संभालने के लिए जिम्मेदार है। इसमें आप [`Resource`](../../aspose.svg.saving/resource/) को स्ट्रीम में सहेज सकते हैं या इसे मूल (पैरेंट) संसाधन में एम्बेड कर सकते हैं। |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | यह विधि संसाधन संदर्भ को संभालने के लिए जिम्मेदार है। इस विधि में आप निर्धारित कर सकते हैं कि संभाले जा रहे संसाधन का संदर्भ कैसे दिखेगा। |

### संबंधित देखें

* class [ResourceHandler](../resourcehandler/)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
