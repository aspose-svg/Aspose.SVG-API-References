---
title: "MediaQueryList क्लास"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "Aspose.Svg.Window.MediaQueryList क्लास। एक MediaQueryList ऑब्जेक्ट दस्तावेज़ पर लागू मीडिया क्वेरी की जानकारी संग्रहीत करता है, जिसमें दस्तावेज़ की स्थिति के विरुद्ध तत्काल और इवेंट-ड्रिवन मिलान दोनों का समर्थन शामिल है। देखें CSSOM View Module विनिर्देश https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs
weight: 5960
url: /hi/net/aspose.svg.window/mediaquerylist/
---
## MediaQueryList class

एक MediaQueryList ऑब्जेक्ट दस्तावेज़ पर लागू मीडिया क्वेरी की जानकारी संग्रहीत करता है, जिसमें दस्तावेज़ की स्थिति के विरुद्ध तत्काल और इवेंट-ड्रिवन मिलान दोनों का समर्थन शामिल है। देखें CSSOM View Module विनिर्देश: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```csharp
public class MediaQueryList : EventTarget
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Document](../../aspose.svg.window/mediaquerylist/document/) { get; } | संदर्भ ऑब्जेक्ट का संबद्ध दस्तावेज़। |
| [Matches](../../aspose.svg.window/mediaquerylist/matches/) { get; } | एक बूलियन मान जो true लौटाता है यदि दस्तावेज़ वर्तमान में मीडिया क्वेरी सूची से मेल खाता है, अन्यथा false। |
| [Media](../../aspose.svg.window/mediaquerylist/media/) { get; } | एक स्ट्रिंग जो क्रमबद्ध (सीरियलाइज़्ड) मीडिया क्वेरी का प्रतिनिधित्व करती है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | एक फ़ंक्शन सेट करता है जो तब बुलाया जाएगा जब निर्दिष्ट इवेंट लक्ष्य को वितरित किया जाएगा। |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | एक फ़ंक्शन सेट करता है जो तब बुलाया जाएगा जब निर्दिष्ट इवेंट लक्ष्य को वितरित किया जाएगा। |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | एक फ़ंक्शन सेट करता है जो तब बुलाया जाएगा जब निर्दिष्ट इवेंट लक्ष्य को वितरित किया जाएगा। |
| [AddListener](../../aspose.svg.window/mediaquerylist/addlistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | MediaQueryList मैच स्थिति परिवर्तन इवेंट लिस्नर जोड़ें। |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | निर्दिष्ट [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) पर एक इवेंट डिस्पैच करता है, (सिंक्रोनस रूप से) प्रभावित EventListeners को उचित क्रम में बुलाता है। सामान्य इवेंट प्रोसेसिंग नियम (कैप्चरिंग और वैकल्पिक बबलिंग चरण सहित) भी उन इवेंट्स पर लागू होते हैं जो मैन्युअली [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/) के साथ डिस्पैच किए जाते हैं। |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | अनमैनेज्ड संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित एप्लिकेशन-परिभाषित कार्य करता है। |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट प्रकार को प्राप्त करने के लिए उपयोग किया जाता है। |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि एक [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) को एक [`EventTarget`](../../aspose.svg.dom/eventtarget/) से हटाया जाता है जबकि वह इवेंट प्रोसेस कर रहा है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। इवेंट लिस्नर्स को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता। |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि एक [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) को एक [`EventTarget`](../../aspose.svg.dom/eventtarget/) से हटाया जाता है जबकि वह इवेंट प्रोसेस कर रहा है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। इवेंट लिस्नर्स को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता। |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि एक [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) को एक [`EventTarget`](../../aspose.svg.dom/eventtarget/) से हटाया जाता है जबकि वह इवेंट प्रोसेस कर रहा है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। इवेंट लिस्नर्स को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता। |
| [RemoveListener](../../aspose.svg.window/mediaquerylist/removelistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | MediaQueryList मैच स्थिति परिवर्तन इवेंट लिस्नर हटाएँ। |

## इवेंट्स

| नाम | विवरण |
| --- | --- |
| event [OnChange](../../aspose.svg.window/mediaquerylist/onchange/) | इवेंट जो MediaQueryList पर तब फायर होता है जब मैच स्थिति बदलती है। |

### संबंधित देखें

* class [EventTarget](../../aspose.svg.dom/eventtarget/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
