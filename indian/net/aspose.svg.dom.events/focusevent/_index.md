---
title: Class FocusEvent
second_title: .NET API संदर्भ के लिए Aspose.SVG
description: Aspose.Svg.Dom.Events.FocusEvent कक्ष. फकसइवेंट इंटरफ़ेस फकस इवेंट्स से जुड़ वशष्ट प्रसंगक जनकर प्रदन करत है
type: docs
weight: 930
url: /hi/net/aspose.svg.dom.events/focusevent/
---
## FocusEvent class

फोकसइवेंट इंटरफ़ेस फोकस इवेंट्स से जुड़ी विशिष्ट प्रासंगिक जानकारी प्रदान करता है।

```csharp
public class FocusEvent : UIEvent
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [FocusEvent](focusevent/#constructor)(string) | का एक नया उदाहरण प्रारंभ करता है`FocusEvent` वर्ग. |
| [FocusEvent](focusevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | का एक नया उदाहरण प्रारंभ करता है`FocusEvent` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि कोई ईवेंट बबलिंग ईवेंट है या नहीं। यदि ईवेंट बबल कर सकता है तो मान सही है, अन्यथा मान गलत है. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि क्या किसी ईवेंट की डिफ़ॉल्ट क्रिया को रोका जा सकता है या नहीं। यदि डिफ़ॉल्ट क्रिया को रोका जा सकता है तो मान सही है, अन्यथा मान गलत है। |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget/) { get; } | इंगित करने के लिए प्रयोग किया जाता है[`IEventTarget`](../ieventtarget/) किसका[`IEventListener`](../ieventlistener/) s वर्तमान में संसाधित किए जा रहे हैं। यह कैप्चरिंग और बबलिंग के दौरान विशेष रूप से उपयोगी है। |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented/) { get; } | सही रिटर्न देता है अगर preventDefault () लागू किया गया था, जबकि रद्द करने योग्य विशेषता मान सही है, और गलत अन्यथा। |
| [Detail](../../aspose.svg.dom.events/uievent/detail/) { get; } | इवेंट के प्रकार के आधार पर, इवेंट के बारे में कुछ विवरण जानकारी निर्दिष्ट करता है. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase/) { get; } | यह इंगित करने के लिए प्रयोग किया जाता है कि वर्तमान में ईवेंट प्रवाह के किस चरण का मूल्यांकन किया जा रहा है। |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted/) { get; } | isTrusted विशेषता को वह मान वापस करना चाहिए जिसके लिए इसे प्रारंभ किया गया था। जब कोई ईवेंट बनाया जाता है तो एट्रिब्यूट को गलत. पर इनिशियलाइज़ किया जाना चाहिए |
| [RelatedTarget](../../aspose.svg.dom.events/focusevent/relatedtarget/) { get; } | इवेंट के प्रकार के आधार पर फ़ोकस ईवेंट से संबंधित द्वितीयक ईवेंट लक्ष्य की पहचान करने के लिए उपयोग किया जाता है। |
| [Target](../../aspose.svg.dom.events/event/target/) { get; } | इंगित करने के लिए प्रयोग किया जाता है[`IEventTarget`](../ieventtarget/) जिसके लिए घटना को मूल रूप से भेजा गया था। |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp/) { get; } | उस समय को निर्दिष्ट करने के लिए उपयोग किया जाता है (युग के सापेक्ष मिलीसेकंड में) जिस पर ईवेंट बनाया गया था। इस तथ्य के कारण कि कुछ सिस्टम यह जानकारी प्रदान नहीं कर सकते हैं, टाइमस्टैम्प का मान सभी घटनाओं के लिए उपलब्ध नहीं हो सकता है। उपलब्ध नहीं होने पर , 0 का मान लौटाया जाएगा. एपोच समय के उदाहरण हैं सिस्टम के प्रारंभ होने का समय या 0:0:0 UTC 1 जनवरी 1970. |
| [Type](../../aspose.svg.dom.events/event/type/) { get; } | इवेंट का नाम (केस-इनसेंसिटिव)। नाम एक XML नाम होना चाहिए. |
| [View](../../aspose.svg.dom.events/uievent/view/) { get; } | दृश्य विशेषता उस विंडो की पहचान करती है जिससे ईवेंट उत्पन्न किया गया था। इस विशेषता का गैर-प्रारंभिक मान शून्य होना चाहिए। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent/)(string, bool, bool) | द[`InitEvent`](../event/initevent/) विधि का उपयोग किसी के मान को प्रारंभ करने के लिए किया जाता है[`Event`](../event/) the द्वारा बनाया गया[`IDocumentEvent`](../idocumentevent/) इंटरफ़ेस. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault/)() | यदि कोई ईवेंट रद्द करने योग्य है, तो[`PreventDefault`](../event/preventdefault/) विधि का उपयोग यह दर्शाने के लिए किया जाता है कि ईवेंट को रद्द किया जाना है, जिसका अर्थ है कि ईवेंट के परिणामस्वरूप कार्यान्वयन द्वारा सामान्य रूप से की जाने वाली कोई भी डिफ़ॉल्ट कार्रवाई नहीं होगी। |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation/)() | इस विधि को लागू करने से ईवेंट को वर्तमान के बाद पंजीकृत किसी भी ईवेंट श्रोताओं तक पहुंचने से रोकता है और जब पेड़ में भेजा जाता है तो ईवेंट को किसी भी अन्य ऑब्जेक्ट तक पहुंचने से रोकता है। |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation/)() | द[`StopPropagation`](../event/stoppropagation/) विधि का उपयोग घटना प्रवाह के दौरान किसी घटना के आगे प्रसार को रोकने के लिए किया जाता है। |

### यह सभी देखें

* class [UIEvent](../uievent/)
* नाम स्थान [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events/)
* सभा [Aspose.SVG](../../)


