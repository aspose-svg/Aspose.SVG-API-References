---
title: "IWindow.Btoa"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "IWindow Btoa मेथड। इनपुट डेटा को Unicode स्ट्रिंग के रूप में लेता है जिसमें केवल U0000 से U00FF रेंज के अक्षर होते हैं, प्रत्येक बाइनरी बाइट को 0x00 से 0xFF मानों के साथ दर्शाते हैं, और इसे उसके base64 प्रतिनिधित्व में बदलकर लौटाता है।"
type: docs
weight: 130
url: /hi/net/aspose.svg.window/iwindow/btoa/
---
## IWindow.Btoa method

इनपुट डेटा को लेता है, जो कि ... के रूप में है, और इसे उसके base64 प्रतिनिधित्व में बदलकर लौटाता है।

```csharp
public string Btoa(string data)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| डेटा | String | Unicode स्ट्रिंग जिसमें केवल U+0000 से U+00FF रेंज के अक्षर होते हैं। |

### रिटर्न वैल्यू

Base64 स्ट्रिंग।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | यदि इनपुट स्ट्रिंग में कोई भी सीमा से बाहर का अक्षर हो तो "InvalidCharacterError" DOMException अपवाद फेंकता है। |

### संबंधित देखें

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
