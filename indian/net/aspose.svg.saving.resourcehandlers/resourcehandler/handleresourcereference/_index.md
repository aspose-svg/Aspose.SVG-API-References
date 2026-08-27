---
title: "ResourceHandler.HandleResourceReference"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "ResourceHandler HandleResourceReference method. यह मेथड संसाधन रेफ़रेंस को संभालने के लिए जिम्मेदार है। इस मेथड में आप सेट कर सकते हैं कि संभाले जा रहे संसाधन का रेफ़रेंस कैसे दिखेगा।"
type: docs
weight: 20
url: /hi/net/aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

यह विधि संसाधन संदर्भ को संभालने के लिए जिम्मेदार है। इस विधि में आप निर्धारित कर सकते हैं कि संभाले जा रहे संसाधन का संदर्भ कैसे दिखेगा।

```csharp
public virtual string HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| resource | Resource | जिस [`Resource`](../../../aspose.svg.saving/resource/) को संभाला जाएगा। |
| संदर्भ | ResourceHandlingContext | संसाधन हैंडलिंग संदर्भ। |

### रिटर्न वैल्यू

एक स्ट्रिंग जो पैरेंट रिसोर्स में लिखी जाएगी और वर्तमान में संभाले जा रहे संसाधन का रेफ़रेंस दर्शाती है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| InvalidOperationException | यदि [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) `null` है और [`Status`](../../../aspose.svg.saving/resource/status/) Saved है तो यह उत्पन्न होता है। सहेजे गए रिसोर्स के लिए [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) निर्दिष्ट किया जाना चाहिए क्योंकि अन्यथा इस रिसोर्स को रेफ़रेंस करने वाले रिसोर्सेज़ में सही रेफ़रेंस निर्दिष्ट करना असंभव है। |

### संबंधित देखें

* class [Resource](../../../aspose.svg.saving/resource/)
* class [ResourceHandlingContext](../../../aspose.svg.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../../)
