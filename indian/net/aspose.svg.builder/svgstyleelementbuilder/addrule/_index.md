---
title: "SVGStyleElementBuilder.AddRule"
second_title: "Aspose.SVG for .NET API संदर्भ"
description: "SVGStyleElementBuilder AddRule मेथड। स्टाइल एलिमेंट में एक CSS नियम जोड़ता है"
type: docs
weight: 30
url: /hi/net/aspose.svg.builder/svgstyleelementbuilder/addrule/
---
## AddRule(*string, string*) {#addrule_1}

शैली तत्व में एक CSS नियम जोड़ता है।

```csharp
public SVGStyleElementBuilder AddRule(string selector, string rules)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| selector | String | नियम के लिए CSS सिलेक्टर। |
| नियम | String | CSS नियम एक स्ट्रिंग के रूप में। |

### रिटर्न वैल्यू

चेनिंग के लिए SVGStyleElementBuilder इंस्टेंस।

### संबंधित देखें

* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRule(*string, Action&lt;RuleBuilder&gt;*) {#addrule}

RuleBuilder का उपयोग करके शैली तत्व में एक CSS नियम जोड़ता है।

```csharp
public SVGStyleElementBuilder AddRule(string selector, Action<RuleBuilder> configureRule)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| selector | String | नियम के लिए CSS सिलेक्टर। |
| configureRule | Action`1 | RuleBuilder का उपयोग करके नियम को कॉन्फ़िगर करने के लिए एक डेलीगेट। |

### रिटर्न वैल्यू

चेनिंग के लिए SVGStyleElementBuilder इंस्टेंस।

### संबंधित देखें

* class [RuleBuilder](../../rulebuilder/)
* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
