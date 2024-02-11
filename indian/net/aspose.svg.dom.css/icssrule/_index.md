---
title: Interface ICSSRule
second_title: .NET API संदर्भ के लिए Aspose.SVG
description: Aspose.Svg.Dom.Css.ICSSRule इंटरफेस. CSSRule इंटरफ़ेस कस भ प्रकर के CSS स्टेटमेंट के लए सर आधर इंटरफ़ेस है इसमें नयम सेट और एटनयम दनं शमल हैं एक कर्यन्वयन से CSS स्टइल शट में नर्दष्ट सभ नयमं क संरक्षत करने क अपेक्ष क जत है भले ह नयम पर्सर द्वर मन्यत प्रप्त न ह अपरचत नयमं क उपयग करके दर्शय गय हैICSSUnknownRule इंटरफ़ेस.
type: docs
weight: 620
url: /hi/net/aspose.svg.dom.css/icssrule/
---
## ICSSRule interface

CSSRule इंटरफ़ेस किसी भी प्रकार के CSS स्टेटमेंट के लिए सार आधार इंटरफ़ेस है। इसमें नियम सेट और एट-नियम दोनों शामिल हैं। एक कार्यान्वयन से CSS स्टाइल शीट में निर्दिष्ट सभी नियमों को संरक्षित करने की अपेक्षा की जाती है, भले ही नियम पार्सर द्वारा मान्यता प्राप्त न हो। अपरिचित नियमों का उपयोग करके दर्शाया गया है!:ICSSUnknownRule इंटरफ़ेस.

```csharp
public interface ICSSRule
```

## गुण

| नाम | विवरण |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssrule/csstext/) { get; set; } | नियम का पार्स करने योग्य शाब्दिक प्रतिनिधित्व। यह नियम की वर्तमान स्थिति को दर्शाता है न कि इसके प्रारंभिक मान को. |
| [ParentRule](../../aspose.svg.dom.css/icssrule/parentrule/) { get; } | यदि यह नियम किसी अन्य नियम (उदाहरण के लिए @मीडिया ब्लॉक के अंदर एक शैली नियम) के अंदर निहित है, तो यह युक्त नियम है। यदि यह नियम किसी अन्य नियम के अंदर नेस्टेड नहीं है, तो यह शून्य वापस आ जाता है। |
| [ParentStyleSheet](../../aspose.svg.dom.css/icssrule/parentstylesheet/) { get; } | स्टाइल शीट जिसमें यह नियम है। |
| [Type](../../aspose.svg.dom.css/icssrule/type/) { get; } | नियम का प्रकार, जैसा कि ऊपर परिभाषित किया गया है। उम्मीद यह है कि बाध्यकारी-विशिष्ट कास्टिंग विधियों का उपयोग CSSRule इंटरफ़ेस के एक उदाहरण से टाइप द्वारा निहित विशिष्ट व्युत्पन्न इंटरफ़ेस में डालने के लिए किया जा सकता है। |

### यह सभी देखें

* नाम स्थान [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* सभा [Aspose.SVG](../../)

