---
title: "ReferrerPolicy एनम"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Builder.ReferrerPolicy एनम। संसाधनों को प्राप्त करते समय उपयोग की जाने वाली रेफ़रर नीति को निर्दिष्ट करता है।"
type: docs
weight: 1020
url: /hi/net/aspose.svg.builder/referrerpolicy/
---
## ReferrerPolicy enumeration

संसाधनों को प्राप्त करते समय उपयोग की जाने वाली रेफ़रर नीति को निर्दिष्ट करता है।

```csharp
public enum ReferrerPolicy
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| None | `0` | कोई रेफ़रर नीति सेट नहीं की गई है। |
| NoReferrer | `1` | Referer हेडर नहीं भेजा जाएगा। |
| NoReferrerWhenDowngrade | `2` | Referer हेडर कम सुरक्षा वाले मूलों (HTTPS -&gt; HTTP) को नहीं भेजा जाएगा। |
| SameOrigin | `3` | Referer हेडर केवल समान-उत्पत्ति अनुरोधों के लिए भेजा जाएगा। |
| Origin | `4` | केवल दस्तावेज़ का मूल Referer हेडर के रूप में भेजा जाएगा। |
| StrictOrigin | `5` | सुरक्षित संदर्भों के लिए केवल दस्तावेज़ का मूल Referer हेडर के रूप में भेजा जाएगा। |
| OriginWhenCrossOrigin | `6` | समान-उत्पत्ति अनुरोधों के लिए पूर्ण URL को Referer हेडर के रूप में भेजा जाएगा, लेकिन क्रॉस-उत्पत्ति अनुरोधों के लिए केवल मूल भेजा जाएगा। |
| StrictOriginWhenCrossOrigin | `7` | समान-उत्पत्ति अनुरोधों के लिए दस्तावेज़ का मूल Referer हेडर के रूप में भेजा जाएगा, लेकिन असुरक्षित संदर्भों में क्रॉस-उत्पत्ति अनुरोधों के लिए कोई हेडर नहीं भेजा जाएगा। |
| UnsafeUrl | `8` | पूर्ण URL, जिसमें पथ और क्वेरी स्ट्रिंग शामिल है, हमेशा Referer हेडर के रूप में भेजा जाएगा। |

### संबंधित देखें

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
