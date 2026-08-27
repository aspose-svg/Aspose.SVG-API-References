---
title: "ResourceHandler क्लास"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Saving.ResourceHandlers.ResourceHandler क्लास। यह क्लास संसाधनों को संभालने के लिए जिम्मेदार है। यह ऐसी विधियाँ प्रदान करती है जो आपको यह नियंत्रित करने देती हैं कि संसाधन के साथ क्या किया जाएगा तथा कौन सा संदर्भ मूल (पैरेंट) संसाधन में लिखा जाएगा।"
type: docs
weight: 5730
url: /hi/net/aspose.svg.saving.resourcehandlers/resourcehandler/
---
## ResourceHandler class

यह क्लास संसाधनों को संभालने के लिए जिम्मेदार है। यह ऐसी विधियाँ प्रदान करती है जो आपको यह नियंत्रित करने देती हैं कि [`Resource`](../../aspose.svg.saving/resource/) के साथ क्या किया जाएगा, साथ ही कौन सा संदर्भ मूल (पैरेंट) [`Resource`](../../aspose.svg.saving/resource/) में लिखा जाएगा।

```csharp
public abstract class ResourceHandler
```

## मेथड्स

| नाम | विवरण |
| --- | --- |
| abstract [HandleResource](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | यह विधि संसाधन को संभालने के लिए जिम्मेदार है। इसमें आप [`Resource`](../../aspose.svg.saving/resource/) को स्ट्रीम में सहेज सकते हैं या इसे मूल (पैरेंट) संसाधन में एम्बेड कर सकते हैं। |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | यह विधि संसाधन संदर्भ को संभालने के लिए जिम्मेदार है। इस विधि में आप निर्धारित कर सकते हैं कि संभाले जा रहे संसाधन का संदर्भ कैसे दिखेगा। |

### संबंधित देखें

* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
