---
title: "IStorage इंटरफ़ेस"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Dom.IStorage इंटरफ़ेस। वेब स्टोरेज API का यह इंटरफ़ेस किसी विशिष्ट डोमेन के सत्र या स्थानीय स्टोरेज तक पहुँच प्रदान करता है। वेब स्टोरेज विनिर्देश देखें https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs
weight: 3090
url: /hi/net/aspose.svg.dom/istorage/
---
## IStorage interface

वेब स्टोरेज API का यह इंटरफ़ेस किसी विशिष्ट डोमेन के सत्र या स्थानीय स्टोरेज तक पहुँच प्रदान करता है। वेब स्टोरेज विनिर्देश देखें: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```csharp
public interface IStorage
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Length](../../aspose.svg.dom/istorage/length/) { get; } | की/मान जोड़े की संख्या लौटाता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Clear](../../aspose.svg.dom/istorage/clear/)() | यदि कोई हों तो सभी की/मान जोड़े हटाता है। |
| [GetItem](../../aspose.svg.dom/istorage/getitem/)(*string*) | दिए गए कुंजी से संबंधित वर्तमान मान लौटाता है, या यदि कुंजी मौजूद नहीं है तो null लौटाता है। |
| [Key](../../aspose.svg.dom/istorage/key/)(*long*) | nth कुंजी का नाम लौटाता है, या यदि n की/मान जोड़े की संख्या से बड़ा या बराबर है तो null लौटाता है। |
| [RemoveItem](../../aspose.svg.dom/istorage/removeitem/)(*string*) | यदि दिए गए कुंजी वाला की/मान जोड़ा मौजूद है तो उसे हटाता है। |
| [SetItem](../../aspose.svg.dom/istorage/setitem/)(*string, string*) | कुंजी द्वारा पहचाने गए जोड़े का मान value पर सेट करता है, यदि पहले कुंजी के लिए कोई की/मान जोड़ा नहीं था तो नया की/मान जोड़ा बनाता है। |

### संबंधित देखें

* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
