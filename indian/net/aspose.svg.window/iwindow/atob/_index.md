---
title: "IWindow.Atob"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "IWindow Atob मेथड। इनपुट डेटा को Unicode स्ट्रिंग के रूप में लेता है जिसमें base64-एन्कोडेड बाइनरी डेटा होता है, इसे डिकोड करता है और एक स्ट्रिंग लौटाता है जिसमें U0000 से U00FF तक के अक्षर होते हैं, प्रत्येक बाइनरी बाइट को 0x00 से 0xFF मानों के साथ दर्शाता है, जो उस बाइनरी डेटा से संबंधित होते हैं।"
type: docs
weight: 120
url: /hi/net/aspose.svg.window/iwindow/atob/
---
## IWindow.Atob method

इनपुट डेटा को Unicode स्ट्रिंग के रूप में लेता है जिसमें base64-एन्कोडेड बाइनरी डेटा होता है, इसे डिकोड करता है, और एक स्ट्रिंग लौटाता है जिसमें U+0000 से U+00FF तक के अक्षर होते हैं, प्रत्येक बाइनरी बाइट को 0x00 से 0xFF मानों के साथ दर्शाता है, जो उस बाइनरी डेटा से संबंधित होते हैं।

```csharp
public string Atob(string data)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| डेटा | String | base64-एन्कोडेड बाइनरी डेटा वाली Unicode स्ट्रिंग |

### रिटर्न वैल्यू

U+0000 से U+00FF तक के अक्षरों वाली स्ट्रिंग

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | यदि इनपुट स्ट्रिंग वैध base64 डेटा नहीं है तो "InvalidCharacterError" DOMException फेंकता है। |

### संबंधित देखें

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
