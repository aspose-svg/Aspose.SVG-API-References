---
title: SVGSVGElement.CreateEvent
second_title: .NET API संदर्भ के लिए Aspose.SVG
description: SVGSVGElement तरक. एक बनत हैEvent कर्यन्वयन द्वर समर्थत एक प्रकर क
type: docs
weight: 110
url: /hi/net/aspose.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

एक बनाता है[`Event`](../../../aspose.svg.dom.events/event/) कार्यान्वयन द्वारा समर्थित एक प्रकार का।

```csharp
public Event CreateEvent(string eventType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| eventType | String | इवेंट टाइप पैरामीटर के प्रकार को निर्दिष्ट करता है[`Event`](../../../aspose.svg.dom.events/event/) बनाया जाने वाला इंटरफ़ेस.  यदि[`Event`](../../../aspose.svg.dom.events/event/)निर्दिष्ट इंटरफ़ेस कार्यान्वयन द्वारा समर्थित है, यह विधि एक new वापस कर देगी[`Event`](../../../aspose.svg.dom.events/event/) अनुरोधित इंटरफ़ेस प्रकार का। यदि[`Event`](../../../aspose.svg.dom.events/event/)के माध्यम से भेजा जाना है[`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) विधि उपयुक्त [`InitEvent`](../../../aspose.svg.dom.events/event/initevent/) आरंभ करने के लिए निर्माण के बाद विधि को बुलाया जाना चाहिए[`Event`](../../../aspose.svg.dom.events/event/) s मान. |

### प्रतिलाभ की मात्रा

नव निर्मित[`Event`](../../../aspose.svg.dom.events/event/)

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: यदि कार्यान्वयन के प्रकार का समर्थन नहीं करता है तो उठाया गया[`Event`](../../../aspose.svg.dom.events/event/) इंटरफ़ेस अनुरोधित |

### यह सभी देखें

* class [Event](../../../aspose.svg.dom.events/event/)
* class [SVGSVGElement](../)
* नाम स्थान [Aspose.Svg](../../svgsvgelement/)
* सभा [Aspose.SVG](../../../)


