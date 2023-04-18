---
title: Class SVGZoomEvent
second_title: .NET API संदर्भ के लिए Aspose.SVG
description: Aspose.Svg.Events.SVGZoomEvent कक्ष. जूम इवेंट तब हत है जब उपयगकर्त एक कर्रवई शुरू करत है ज एसवज दस्तवेज़ खंड के वर्तमन दृश्य क फर से स्केल करने क करण बनत है इवेंट हैंडलर केवल svg एलमेंट्स पर पहचने जते हैं
type: docs
weight: 1620
url: /hi/net/aspose.svg.events/svgzoomevent/
---
## SVGZoomEvent class

जूम इवेंट तब होता है जब उपयोगकर्ता एक कार्रवाई शुरू करता है जो एसवीजी दस्तावेज़ खंड के वर्तमान दृश्य को फिर से स्केल करने का कारण बनता है। इवेंट हैंडलर केवल 'svg' एलिमेंट्स पर पहचाने जाते हैं।

```csharp
public class SVGZoomEvent : Event
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि कोई ईवेंट बबलिंग ईवेंट है या नहीं। यदि ईवेंट बबल कर सकता है तो मान सही है, अन्यथा मान गलत है. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि क्या किसी ईवेंट की डिफ़ॉल्ट क्रिया को रोका जा सकता है या नहीं। यदि डिफ़ॉल्ट क्रिया को रोका जा सकता है तो मान सही है, अन्यथा मान गलत है। |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | इंगित करने के लिए प्रयोग किया जाता है[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) किसका[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) s वर्तमान में संसाधित किए जा रहे हैं। यह कैप्चरिंग और बबलिंग के दौरान विशेष रूप से उपयोगी है। |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | सही रिटर्न देता है अगर preventDefault () लागू किया गया था, जबकि रद्द करने योग्य विशेषता मान सही है, और गलत अन्यथा। |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि वर्तमान में ईवेंट प्रवाह के किस चरण का मूल्यांकन किया जा रहा है। |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted विशेषता को वह मान वापस करना चाहिए जिसके लिए इसे प्रारंभ किया गया था। जब कोई ईवेंट बनाया जाता है तो एट्रिब्यूट को गलत. पर इनिशियलाइज़ किया जाना चाहिए |
| [NewScale](../../aspose.svg.events/svgzoomevent/newscale/) { get; } | स्केल फ़ैक्टर जो ज़ूम ऑपरेशन के संसाधित होने के बाद होगा। |
| [NewTranslate](../../aspose.svg.events/svgzoomevent/newtranslate/) { get; } | अनुवाद मान जो ज़ूम ऑपरेशन के संसाधित होने के बाद होगा। SVGPoint ऑब्जेक्ट केवल पढ़ने के लिए है। |
| [PreviousScale](../../aspose.svg.events/svgzoomevent/previousscale/) { get; } | पिछले ज़ूम ऑपरेशंस से स्केल फ़ैक्टर जो ज़ूम ऑपरेशंस होने से पहले था। |
| [PreviousTranslate](../../aspose.svg.events/svgzoomevent/previoustranslate/) { get; } | पिछले ज़ूम ऑपरेशंस से अनुवाद मान जो ज़ूम ऑपरेशंस होने से पहले थे। SVGPoint ऑब्जेक्ट केवल पढ़ने के लिए है। |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | इंगित करने के लिए प्रयोग किया जाता है[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) जिसके लिए घटना को मूल रूप से भेजा गया था। |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | उस समय को निर्दिष्ट करने के लिए उपयोग किया जाता है (युग के सापेक्ष मिलीसेकंड में) जिस पर ईवेंट बनाया गया था। इस तथ्य के कारण कि कुछ सिस्टम यह जानकारी प्रदान नहीं कर सकते हैं, टाइमस्टैम्प का मान सभी घटनाओं के लिए उपलब्ध नहीं हो सकता है। उपलब्ध नहीं होने पर , 0 का मान लौटाया जाएगा. एपोच समय के उदाहरण हैं सिस्टम के प्रारंभ होने का समय या 0:0:0 UTC 1 जनवरी 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | इवेंट का नाम (केस-इनसेंसिटिव)। नाम एक XML नाम होना चाहिए. |
| [ZoomRectScreen](../../aspose.svg.events/svgzoomevent/zoomrectscreen/) { get; } | स्क्रीन इकाइयों में निर्दिष्ट ज़ूम आयत। SVGRect ऑब्जेक्ट केवल पढ़ने के लिए है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(string, bool, bool) | द[`InitEvent`](../../aspose.svg.dom.events/event/initevent/) विधि का उपयोग किसी के मान को प्रारंभ करने के लिए किया जाता है[`Event`](../../aspose.svg.dom.events/event/) the द्वारा बनाया गया[`IDocumentEvent`](../../aspose.svg.dom.events/idocumentevent/) इंटरफ़ेस. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | यदि कोई ईवेंट रद्द करने योग्य है, तो[`PreventDefault`](../../aspose.svg.dom.events/event/preventdefault/) विधि का उपयोग यह दर्शाने के लिए किया जाता है कि ईवेंट को रद्द किया जाना है, जिसका अर्थ है कि ईवेंट के परिणामस्वरूप कार्यान्वयन द्वारा सामान्य रूप से की जाने वाली कोई भी डिफ़ॉल्ट कार्रवाई नहीं होगी। |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | इस विधि को लागू करने से ईवेंट को वर्तमान के बाद पंजीकृत किसी भी ईवेंट श्रोताओं तक पहुंचने से रोकता है और जब पेड़ में भेजा जाता है तो ईवेंट को किसी भी अन्य ऑब्जेक्ट तक पहुंचने से रोकता है। |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | द[`StopPropagation`](../../aspose.svg.dom.events/event/stoppropagation/) विधि का उपयोग घटना प्रवाह के दौरान किसी घटना के आगे प्रसार को रोकने के लिए किया जाता है। |

### यह सभी देखें

* class [Event](../../aspose.svg.dom.events/event/)
* नाम स्थान [Aspose.Svg.Events](../../aspose.svg.events/)
* सभा [Aspose.SVG](../../)


