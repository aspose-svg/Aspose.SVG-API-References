---
title: "Resource.Embed"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Resource Embed मेथड। यह इस संसाधन को उसके पैरेंट में Base64 एन्कोड करके एम्बेड करता है। एन्कोडिंग परिणाम OutputUrl में लिखा जाएगा।"
type: docs
weight: 60
url: /hi/net/aspose.svg.saving/resource/embed/
---
## Resource.Embed method

इस संसाधन को उसके पैरेंट में Base64 एन्कोड करके एम्बेड करता है। एन्कोडिंग परिणाम [`OutputUrl`](../outputurl/) में लिखा जाएगा।

```csharp
public Resource Embed(ResourceHandlingContext context)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| संदर्भ | ResourceHandlingContext | संसाधन हैंडलिंग संदर्भ। |

### रिटर्न वैल्यू

यह संसाधन ताकि आप कॉल्स को चेन कर सकें।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| InvalidOperationException | यदि कोई [`ParentResource`](../../resourcehandlingcontext/parentresource/) नहीं है तो यह उठाया जाता है क्योंकि परिणाम को एम्बेड करने की कोई जगह नहीं है। |

### संबंधित देखें

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
