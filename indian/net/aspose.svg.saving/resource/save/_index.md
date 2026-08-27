---
title: "Resource.Save"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Resource Save मेथड। यह प्रदान किए गए स्ट्रीम में संसाधन को सहेजता है।"
type: docs
weight: 70
url: /hi/net/aspose.svg.saving/resource/save/
---
## Resource.Save method

प्रदान किए गए स्ट्रीम में संसाधन को सहेजता है।

```csharp
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | स्ट्रीम जिसमें संसाधन सहेजा जाएगा। |
| संदर्भ | ResourceHandlingContext | संसाधन हैंडलिंग संदर्भ। |

### रिटर्न वैल्यू

यह संसाधन ताकि आप कॉल्स को चेन कर सकें।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| InvalidOperationException | यदि [`OutputUrl`](../outputurl/) `null` है तो यह उठाया जाता है। [`OutputUrl`](../outputurl/) को संसाधन को सहेजने से पहले निर्दिष्ट किया जाना चाहिए क्योंकि अन्यथा इस संसाधन को संदर्भित करने वाले संसाधनों में सही रेफ़रेंस निर्दिष्ट करना असंभव है। |

### संबंधित देखें

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
